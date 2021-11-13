Arch Linux

1. Install Arch Linux following guide
1.1 Install vim, networkmanager grub and efibootmgr before reboot
    Pacman -S vim grub efibootmgr networkmanager

2. Create a user and setup sudoer
    Pacman -S vi sudo
    sudoer edit /etc/sudoers

3. Install yay
    Pacman -S git base-devel
    git clone ...
    makepkg -si

4. Install a tiling window manager like i3 and a desktop manager like lightdm and a greeter
    Pacman -S i3 xorg lightdm and gtk-greeter autotiling

5. Install google-chrome-stable
6. Install font
    awesome-terminal-font for better icon

7. Install alsa-utils pulseaudio-alsa pavucontrol pasystray for sound

8. Install feh for background picture

9. Install nvida driver and picom for transparent

10. Run arandr for multiple display settings

11. install nm-applet xss-lock for i3 xsession errors

12. install fcitx5-im fcitx-addon for input method

13. install gluqlo & xscreensaver for screen saver

14. install sdl sdl_ttf sdx_xxx

15. install linux-lts linux-lts-headers and nvidia-lts

16. install pcmanfm for file manager

17. install startship for prompt and install rust tools

18. install lxappearance dconf-editor for theme

19. Install bumblebee-status for a better i3bar

20. Setup power
	a. /etc/systemd/logind.conf
	b. xset q; xset -dpms

21. Install cronie
	sudo systemctl start cronie
	sudo systemctl enable cronie
	cron -e
	cron -l
