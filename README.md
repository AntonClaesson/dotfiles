# Dotfiles
Tracking of config files in .configs/ inspired by https://www.atlassian.com/git/tutorials/dotfiles

## Linux environment setup

Setup a linux environment with the stored zsh and tmux configuration:

**With curl**
```bash 
apt-get update && apt-get install -y curl
bash <(curl -sSL https://gist.githubusercontent.com/AntonClaesson/8a08ae6a11224c5b1d2acb2f92a508c8/raw/c50a6079b0f3c67fabea16f644e31f756d81a72a/setup-linux-curl.sh)
```
**With wget**
```bash
apt-get update && apt-get install -y wget
bash <(wget -O - https://gist.githubusercontent.com/AntonClaesson/a90200b3517b8569cb0ce4b993b4f308/raw/6b0a150114ead7f941a3b5c180772ebe65c09d60/setup-linux-wget.sh)
```
