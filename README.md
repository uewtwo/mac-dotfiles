# How To Use
```
git clone https://github.com/andsens/homeshick.git $HOME/.homesick/repos/homeshick
printf '\nsource "$HOME/.homesick/repos/homeshick/homeshick.sh"' >> $HOME/.zshrc
printf '\nsource "$HOME/.homesick/repos/homeshick/completions/homeshick-completion.bash"' >> $HOME/.zshrc
source $HOME/.zshrc
homeshick clone https://github.com/uewtwo/mac-dotfiles.git
cd $HOME/.homesick/repos/dotfiles
git submodule init
git submodule update
homeshick symlink dotfiles
```
