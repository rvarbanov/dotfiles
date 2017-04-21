dotfiles
--------

Radi's dotfiles

To use them:
```
$ brew install stow
$ cd ~
$ git clone https://github.com/rvarbanov/dotfiles.git
$ cd dotfiles
$ ./install.sh
```

I am using GNU stow to symlink the configuration files to my home directory.
The stow commands are in ```install.sh```, as well as some other things.

There is also an ```uninstall.sh``` to clean up if you like.

TODO:

1. move existing folders to `temp-dotfiles-{timestamp}`
2. copy seoul256 to .vim/color/
3. install Ack/ag/ctrlp.vim ?
4. vim +PluginInstall +qall


ctrl-w w or ctrl-h,j,k,l
:vsp || :sp
ctrl-a s || v
fzf???

zsh-syntax-highlighting: unhandled ZLE widget 'history-substring-search-up'
zsh-syntax-highlighting: (This is sometimes caused by doing `bindkey <keys> history-substring-search-up` without creating the 'history-substring-search-up' widget with `zle -N` or `zle -C`.)
zsh-syntax-highlighting: unhandled ZLE widget 'history-substring-search-down'
zsh-syntax-highlighting: (This is sometimes caused by doing `bindkey <keys> history-substring-search-down` without creating the 'history-substring-search-down' widget with `zle -N` or `zle -C`.)
