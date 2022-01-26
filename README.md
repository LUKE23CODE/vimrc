# vimrc

## How to install my vimrc file?

1. Install Vim on your system
2. Create a .vimrc file in your home directory -> /users/john/.vimrc | $HOME/.vimrc | ~/.vimrc
3. Open up the .vimrc file & copy the contents of my vimrc.bak into your .vimrc file and the save and exit the .vimrc file with :wq
4. Open a new vim session and in normal mode type :PlugInstall and press enter. This will download the plugins into ~/.vim/plugged/ folder.
5. Exit that session again with :q and restart vim and you are done.

## Plugins that I use?

1. polyglot -> a language pack for Vim that provides syntax highlighting and indentation for lots and lots of programming languages.
2. gruvbox -> this is the theme that i am using for syntax highlighting
3. auto-pairs -> Insert or delete brackets, parenteses, quotes in pair.
4. nerdtree -> this give you a file browser on the left of the window.
5. jedi-vim -> a VIM binding to the autocompletion library Jedi.
6. seoul256 -> this is also a theme
7. coc.nvim -> this is to provide full language server protocol on vim and neovim.
8. vim-commentary -> this is used to comment and uncomment code with gcc & gc.

## Keybindings

1. the leader key is <SPACE>
2. To toggle nerdtree on and off use <F2> key
3. To open integrated terminal press <C-t> -> ctrl-t
4. To rename something press <SPACE>rn
