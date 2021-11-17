# dotfiles

# TODO
- Something about my script I think makes the home directory owned by root, so until I fix the script, run `sudo chown $USER:$USER ~ -R`

# Setup

1. Setup and open WSL
2. `cd ~ && sudo apt-get update && sudo apt-get install wget`
4. `wget https://github.com/shanrauf/dotfiles/raw/main/setup.sh`
5. `chmod u+x setup.sh`
6. `sudo ./setup.sh`
