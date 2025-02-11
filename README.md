# Dotfiles

Right now, this only houses my .zshrc file

## Required packages

* fzf
* eza
* cowsay
* fortune

# Configuration

Install zsh, then Oh My Zsh, and copy the .zshrc file to the home directory, don´t forget to append the dot to the zshrc file. 

**Fix Alt Tab in  gnome**

gsettings set org.gnome.desktop.wm.keybindings switch-applications "[]"

gsettings set org.gnome.desktop.wm.keybindings switch-windows "['<Alt>Tab', '<Super>Tab']"
