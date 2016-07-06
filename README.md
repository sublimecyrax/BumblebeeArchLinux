# This brief tutorial in the form of a code
# For more FAQ visit to Wiki-Page
`sudo pacman -S mesa xf86-video-intel xf86-input-mouse xf86-input-synaptics xf86-input-keyboard`
`sudo pacman -S bumblebee`
`sudo gpasswd -a USER bumblebee`
`sudo pacman -S nvidia nvidia-utils bbswitch primus mesa-demos mesa-libgl`
`sudo systemctl enable bumblebeed.service && sudo reboot`
`sudo mkinitcpio -p linux && sudo grub-mkconfig -o /boot/grub/grub.cfg`
`optirun --status`
`optirun glxspheres64`  `vblank_mode=0 primusrun glxspheres64`


