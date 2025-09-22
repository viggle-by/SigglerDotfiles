# SigglerDotfiles
dfdfddfvfdf

#### hyeee
git clone https://github.com/viggle-by/SigglerDotfiles.git ~/.dotfiles

ln -s ~/.dotfiles/.zshrc ~/.zshrc
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew bundle --file ~/.dotfiles/Brewfile
