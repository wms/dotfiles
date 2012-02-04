#my dotfiles.

##vim

My .vimrc uses Derek Wyatt's vim configuration -
https://github.com/derekwyatt/vim-config - as a base. I've stripped a lot of
things that I have no cause to use and included only one colour scheme
(xoria256) and plugin (NERD Tree).

Assuming you cloned this repo to `$HOME/dotfiles`, then the best way to source
these files is to put the following in `$HOME/.vimrc`:

    set runtimepath+=~/dotfiles/vim
    path+=~/dotfiles/vim
    source ~/dotfiles/.vimrc
