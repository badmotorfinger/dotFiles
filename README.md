# homeConfigs
Linux dot file configuration

### On a new machine

Prior to the installation make sure you have committed the alias to your .bashrc or .zsh:

`alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'`

Now clone your dotfiles into a bare repository in a "dot" folder of your $HOME:

`git clone --bare git@github.com:badmotorfinger/homeConfigs.git .dotFiles`

`config checkout`
