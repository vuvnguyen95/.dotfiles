# My Dotfiles
These are my dotfile configuration files for different software in Bash.
## .vimrc
This is my custom .vimrc configuration for Vim.
## .bashrc
This is my custom .bashrc configuration for Bash.
## Installing Tools:
I setup my environment primarily using the Makefile and passing in the corresponding platform name. As of now the following Makefile targets are supported which runs their respective setup scripts:
- linux.sh

Simply run make \<target> to use call the respective scripts.

## Clean up Tools:
You can run make clean to clean up what created while running the script. This make clean command runs on cleanup.sh

## Current Features:


