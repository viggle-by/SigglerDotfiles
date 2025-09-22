# SigglerDotfiles
dfdfddfvfdf

#### hyeee
```sh
git clone https://github.com/viggle-by/SigglerDotfiles.git ~/.dotfiles
ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew bundle --file ~/.dotfiles/Brewfile

sudo add-apt-repository ppa:zhangsongcui3371/fastfetch
sudo apt install fastfetch
