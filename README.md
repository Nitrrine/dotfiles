![Preview](https://github.com/user-attachments/assets/98e14c3b-ede4-406f-a098-aa664498cb25)


# dotfiles

Just my dotfiles and nothing else. I've provided some small documentation below. Contributions are welcome!

## Summary

Distro: **Arch Linux**

Protocol: **Wayland**

Window Manager: **Hyprland**

Wallpaper: **Arch Linux [3840×2160]** ([source](https://www.reddit.com/r/wallpaper/comments/mbmps9/arch_linux_38402160/))

App Launcher: **Tofi**

Audio Server: **PipeWire**

File Manager: **Thunar**

Font Family: **JetBrains Mono**

Theme: **Cappuccin Frappe**

## Requirements

Make sure to install requirements so dotfiles will work correctly. 
I'm using [paru](https://github.com/morganamilo/paru) the AUR helper for everything, you can use pacman.

### Git
```
$ paru -S git
```

### Stow
```
$ paru -S stow
```

### Fonts
```
$ paru -S ttf-jetbrains-mono otf-font-awesome
```

### Thunar
```
$ paru -S thunar
```

### Waybar
```
$ paru -S waybar
```

### Hyprland

For installing Hyprland tiling compositor please follow instructions on Arch Wiki: 
https://wiki.archlinux.org/title/Hyprland .

## Installation

Clone this repo into your home directory, then cd into it.

```
$ git clone https://github.com/Nitrrine/dotfiles.git
$ cd dotfiles
```

After this, use GNU Stow to generate symlinks.

```
$ stow .
```
