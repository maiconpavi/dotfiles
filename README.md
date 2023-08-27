# dotfiles

## Installation

```bash
git clone --bare git@github.com:maiconpavi/dotfiles.git $HOME/.cfg
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
config checkout
config config --local status.showUntrackedFiles no
```
