# dotfiles

## Installation

```bash
git clone --bare git@github.com:maiconpavi/dotfiles.git $HOME/.cfg
echo "alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'" >> $HOME/.bashrc
config checkout
config config --local status.showUntrackedFiles no
```
