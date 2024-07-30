![Preview](https://github.com/user-attachments/assets/de7b01c6-8650-42b0-b9bd-0e1dd11e7aa7)

# dotfiles

Just my dotfiles and nothing else. I've provided some small documentation below. Contributions are welcome!

## Summary

Distro: **Arch Linux**

Window Manager: **Hyprland (Wayland)**

Wallpaper: **Arch Linux [3840×2160]** ([source](https://www.reddit.com/r/wallpaper/comments/mbmps9/arch_linux_38402160/))

Application Launcher: **Tofi**

Audio Server: **PipeWire**

File Manager: **Thunar**

Font Family: **JetBrains Mono**

Terminal: **Alacritty**

Theme: **Cappuccin Frappe**

## Requirements

Make sure to install requirements so dotfiles will work correctly. 
I'm using [paru](https://github.com/morganamilo/paru) as AUR helper, however you can use [yay](https://github.com/Jguer/yay).

## Dependencies

```
$ paru -S git stow thunar alacritty hyprland hyprpaper hypridle hyprlock waybar dunst tofi pipewire pipewire-alsa pipewire-pulse alsa-utils gtk3 gtk4 nwg-look ttf-jetbrains-mono otf-font-awesome
```

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
