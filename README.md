# Xmonad config

This is Xmonad window manager config usually i use.

## Dependencies

Arch Linux

```bash
pacman -S xmonad xmonad-contrib xmobar stalonetray ttf-fira-code
```

AUR
```bash
# With AUR helper

yay -S nerd-fonts-fira-code
# or
paru -S nerd-fonts-fira-code

# real chad use 
git clone https://aur.archlinux.org/nerd-fonts-fira-code.git
cd nerd-fonts-fira-code
makepkg -si
```

## Usage
```bash
git clone https://github.com/cnugroho11/xmonad-arch-config.git
cd xmonad-arch-config

mkdir ~/.xmonad
cp xmonad.hs ~/.xmonad/
cp .xmobarrc ~/
cp .stalonetrayrc ~/
cp .xprofile ~/

# restart xmonad with pressing modkey + shift + q
```

