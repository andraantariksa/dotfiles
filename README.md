# Dotfiles

My personal dot files for linux systems

## Installation

```
cd ~
# Don't use git clone, git will get angry
git init
git remote add origin https://github.com/andraantariksa/dotfiles.git
mv .bashrc .bashrc.backup
git pull https://github.com/andraantariksa/dotfiles.git
git branch --set-upstream-to=origin/master master
git pull
source ~/.bashrc
```
