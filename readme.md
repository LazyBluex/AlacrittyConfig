## install alacritty
sudo apt update -y && sudo apt upgrade -y
sudo add-apt-repository ppa:aslatter/ppa -y
sudo apt update -y
sudo apt install alacritty -y

## set default
gsettings set org.gnome.desktop.default-applications.terminal exec /usr/bin/alacritty

## config
git clone https://github.com/LazyBluex/AlacrittyConfig.git ~/.config/alacritty
