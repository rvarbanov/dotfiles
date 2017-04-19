dotfiles
--------

Radi's dotfiles

To use them:
```
$ cd ~
$ git clone https://github.com/rvarbanov/dotfiles.git
$ cd dotfiles
$ ./install.sh
```

I am using GNU stow to symlink the configuration files to my home directory.
The stow commands are in ```install.sh```, as well as some other things.

There is also an ```uninstall.sh``` to clean up if you like.
