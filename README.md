# This brief tutorial in the form of a console code
# For more FAQ visit to Wiki-Page

`sudo pacman -S nvidia nvidia-utils bbswitch primus mesa-demos mesa-libgl`

`sudo pacman -S bumblebee`

`sudo gpasswd -a USER bumblebee`

`sudo systemctl enable bumblebeed.service && sudo reboot`

`sudo mkinitcpio -p linux && sudo grub-mkconfig -o /boot/grub/grub.cfg`

`optirun --status`

`optirun glxspheres64`  `vblank_mode=0 primusrun glxspheres64`


