## Install Basic Packages

```
sudo pacman -S alacritty feh picom rofi zathura polybar exa starship pulseaudio pulseaudio-alsa
```

```
paru -S nordic-theme
```

## Use Configuration Manually

```
cp -r dotfiles/{i3,alacritty,picom,polybar,rofi,gtk-3.0,zathura} ~/.config
```

## Set Wallpaper

```
mkdir ~/Pictures

cp dotfiles/1.png ~/Pictures
```

## Set Bash Configuration

```
cp dotfiles/.bashrc ~/
```
