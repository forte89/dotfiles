dotfiles
========

My dotfiles to be shared easily across computers

This is the usual workflow when I format, change of OS or fully upgrade a machine:
  * format to start fresh
  * run the corresponding install script to that machine (found in the [installs repo][installrepo]) 
  * pull this dotfiles
  * Enjoy 

All vim plugins (including [Pathogen][pathogen] itself) is contained in its own git submodule!

The <code>bootstrap.sh</code> script comes from [Mathias Bynens dotfiles][mathias]

I though of updating submodules (vim plugins) automatically after rsyncing files to home directory but it is too dangerous for me.

Todo
----
  * add mapping to .vimrc to make it toggle the 81st column marker too, when toggling list! (viewing tabs and returns - <leader>l)

[installrepo]: https://github.com/disrupts/installs
[mathias]:     https://github.com/mathiasbynens/dotfiles
[pathogen]:    https://github.com/tpope/vim-pathogen
