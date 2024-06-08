# Min Dark - GRUB Theme

This is a personal custom GRUB menu theme, i wanted something that looked modern and pretty but it would still looks like a Linux desktop and when i was searching for themes online i only founded one or another so i decided to make my own.

This will only work with 1920x1080 displays.

## How to install a GRUB theme:

If you founded this repo, liked the theme and wants to try it out, you just have to follow this steps:

- Download the theme by cloning the repo or downloading the zip;

- Extract the theme to /boot/grub/themes/;

- Edit /etc/default/grub file. Find the line starting with "#GRUB_THEME" (or create it) and change it to "GRUB_THEME=/boot/grub/themes/[THEME_FOLDER]/theme.txt" (replace [THEME_FOLDER] with the real theme name);

- Run "sudo update-grub" (for debian based distros) or "sudo grub-mkconfig -o /boot/grub/grub.cfg" (for arch/manjaro);

See more about GRUB: https://en.wikipedia.org/wiki/Grand_Unified_Bootloader
