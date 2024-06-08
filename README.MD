# Min Dark - GRUB Theme

This is a personal custom GRUB menu theme, I wanted something that looked modern and pretty but it would still looks like a Linux desktop and when I was searching for themes online I only founded one or another so I decided to make my own.

This will only work with 1920x1080 displays.

![Preview](https://raw.githubusercontent.com/kenaioz/grub-min-theme/main/assets/preview.png)
(One day I will test this theme in a VM to take a proper screenshot)

If this theme starts to get some users maybe I will make some variants with other manufacturers besides ASRock and with some distro logos.

## How to install a GRUB theme:

If you found this repo, liked the theme and want to try it out, you just have to follow these steps:

- Download the theme by cloning the repo or downloading the zip;

- Extract the theme to /boot/grub/themes/;

- Edit /etc/default/grub file. Find the line starting with "#GRUB_THEME" (or create it) and change it to "GRUB_THEME=/boot/grub/themes/[THEME_FOLDER]/theme.txt" (replace [THEME_FOLDER] with the real theme name);

- Run `sudo update-grub` (for Debian-based distros) or `sudo grub-mkconfig -o /boot/grub/grub.cfg` (for Arch/Manjaro).

See more about GRUB: https://en.wikipedia.org/wiki/Grand_Unified_Bootloader
