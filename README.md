# VIM setup

## Install

1. Install NeoVim: `brew install nvim`
2. Install the Roboto Mono Nerd Font
3. Run `cp /Development/vim/nvim/* .`
4. Start NeoVim by running `nvim`
5. Install `vim-plug`  
6. Enter `:PlugInstall` to intall all the plugins specified in init.vim

## Usage

Open a entire folder by running `nvim <FOLDER_PATH>`.
Now if you open the folder tree with F2 you'll find all your files there.
Hit `Tab` to preview a file & `Enter` to open a file. You can also use `w` to open a file in split view.
More info on how to use the file tree [here](https://github.com/ms-jpq/chadtre).

Once you have multiple buffers open (by opening a file) you can move around with `Ctrl + w + w`.
To start editing a file press `I` to go into edit mode. Once you are done editing press `Esc` to quit edit mode.
Save a file with `:w` and close it with `:q`.

