# dotconfig - ~/. configuration files

# Installation:
## Font
### Agave Nerd Font (v3.0.2):
#### In Arch Linux:
```
sudo pacman -S ttf-agave-nerd
```
#### Other distros:
```
aria2c "https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/Agave.zip"
mkdir -p ~/.local/share/fonts/
unzip Agave.zip -d ~/.local/share/fonts/
fc-cache -fv
```

## Vim (tested with 9.0.1642)
### Install coc.nvim plugins:
```
cp .vimrc ~/.vimrc
vim -c "CocInstall coc-jedi coc-html coc-css coc-sh coc-go coc-tabnine coc-word"
```

## Konsole (tested with 20.12.3)
### Profile `Brazers` (sorry for such name =\ ):
```
cp .local/share/konsole/Brazers.profile ~/.local/share/konsole/Brazers.profile
cp .config/konsolerc ~/.config/konsolerc
```
