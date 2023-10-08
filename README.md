# dotconfig - ~/. configuration files

# Installation:
## Font
- https://dev.to/moniquelive/using-nerd-font-symbols-and-emoji-with-any-unpatched-font-in-linux-3kdo
```
sudo pacman -S ttf-jetbrains-mono-nerd noto-fonts-emoji
fc-cache -fv
```

## Vim (tested with 9.0.1642)
### Install coc.nvim plugins:
```
cp .vimrc ~/.vimrc
vim -c "CocInstall coc-jedi coc-tsserver coc-html coc-css coc-sh coc-go coc-tabnine coc-word"
```

## Konsole (tested with 20.12.3)
### Profile `Brazers` (sorry for such name =\ ):
```
cp .local/share/konsole/Brazers.profile ~/.local/share/konsole/Brazers.profile
cp .config/konsolerc ~/.config/konsolerc
```
