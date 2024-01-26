# Dotfiles
Tracking of config files in .configs/ inspired by https://www.atlassian.com/git/tutorials/dotfiles

## Setup
To use these configs, just clone the repo to `~/dotfiles`
```
cd ~
git clone git@github.com:AntonClaesson/dotfiles.git
```

## Tmux
To configure tmux correctly you might need to run (outside of session)
```
tmux source ~/.config/tmux/tmux.conf
```
then inside a session you can install and refresh if needed using
`ctrl+space+I` or `ctrl+b+I` if first does not work.
