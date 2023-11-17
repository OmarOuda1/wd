# wd

This is a rewrite of warp directory because I don't use ohmyzsh.

## The Originals [wd(ohmyzsh)](https://github.com/mfaerevaag/wd) [wd(bash)](https://github.com/troyxmccall/wd)

## Note This script only works in zsh if you want something for bash consider using [wd(bash)](https://github.com/troyxmccall/wd)

## How to install

To use it you need to add an alias or a function to your zshrc to source the script.
you can store the script any where you just need to source it.

## Commands to use

{ list , add , conf , nvim , ls , code }
Type **list** to list all the available directories to warp to.
Type **conf** to open the config file stored at ~/.config/wd.conf in neovim.
Type **add** then a name to add the current working directory (PWD) to your warp list.
Type a name of a warp point to cd to this directory you can add a path after the point like in the following example `wd point /directory-inside-the-warp-point`.
Type **ls** to list the contents of a warp point and you can use the same syntax of adding a path after your point to ls that path.
Type **code** to open warp point in vscode
Type **nvim** to open warp point in nvim
