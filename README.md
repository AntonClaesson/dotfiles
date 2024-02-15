# Dotfiles
Tracking of config files in .configs/ inspired by https://www.atlassian.com/git/tutorials/dotfiles

## Linux environment setup
To setup a linux environment with the stored zsh and tmux configuration, run the follwing:
```bash
apt-get update && apt-get install -y curl
bash <(curl -sSL https://gist.githubusercontent.com/AntonClaesson/8a08ae6a11224c5b1d2acb2f92a508c8/raw/50b2ae1034f15bf1e1c4715e174e360ec4f46fa2/setup-linux.sh)
```
Reload the shell by running
```bash
exec zsh
```
Finally, you might need to log out and log back in to get zsh as your default shell.
