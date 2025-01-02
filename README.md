
# My personal configuration
## Dependencies 

Arch Linux:

```bash
  pacman -S hyprland rofi pavucontrol dunst waybar xdg-desktop-portal-hyprland dolphin kitty firefox swaybg
```


## Shortcuts
|Keys |Action|
|-----|--------|
|SUPER + Q| close window     |
|SUPER + B |open Firefox      |
|SUPER + T |open Telegram      |
|SUPER + F |enable fullscreen      |
|SUPER + RETURN |Kitty     |
|SUPERSHIFT + Q |close Hyprland session     |
|SUPER + E | Dolphin      |
|SUPER + D |Rofi      |
|SUPER + S |split windows     |
|SUPER + SPACE |enable floating      |
|VOL UP |increase 5% audio      |
|VOL DOWN |decrease 5% audio      |
|MUTE|mute audio      |
|ALT + TAB |focus on next window      |
|SUPER + LEFT CLICK | drag and move window      |
|SUPER + RIGHT CLICK |resize window     |
|SUPER + LEFT ARROW |resize window      |
|SUPER + RIGHT ARROW |resize window      |
|SUPERSHIFT + LEFT ARROW |move active window left      |
|SUPERSHIFT + RIGHT ARROW |move active window right      |
|SUPER + mouse wheel down |go to previous workspace     |
|SUPER + mouse wheel up|go to next workspace    |
|SUPER + O|hide/unhide status bar|
|SUPER + SHIFT + W|change wallpaper|


## FAQ

#### Telegram is not working.

In my config, Telegram is under /usr/local/bin. If you are using a distro package just change with 'telegram-desktop'.

#### On waybar temperature is not working nor incorrect.

Go to ```.config/waybar/config.jsonc```, look and change hwmon-path according to your machine fits.

To determine your CPU, GPU, NVME:

 (example)  ``` cat /sys/class/hwmon/hwmon0/name```

