# WARNING this software is not longer mantained, it has been moved [here](https://github.com/TheNaoX/dotfiles)
# Vim for Rails

## The necessary configuration to have the syntax highlight and shortcuts to vim, MacVim or Gvim

Some features include:

* nice theme for gui and terminal with 16 colors. (ir_black and xterm16)
* incremental Search that ignore case by default
* Swap and backup out of your way

To install:
You need to install gnome-vim. If you are using Ubuntu you can run:

 `sudo apt-get install gnome-vim`

then add the config files:

 `git clone git://github.com/TheNaoX/Vim-for-Rails.git ~/.vim`

  `cd ~/.vim`

  `./install.sh`

# USAGE
     -----------------------------------------------------------------------------  
     |                            VIM Settings                                   |
     |                   (see gvimrc for gui vim settings)                       |
     |                                                                           |
     | Some highlights:                                                          |
     |   jj = <esc>  Very useful for keeping your hands on the home row          |
     |   ,n = toggle NERDTree off and on                                         |
     |   ,N = find current file in  NERDTree                                     |
     |                                                                           |
     |   ,FC = fuzzy find coverage files (or ,f)                                 |
     |   ,FF = fuzzy find files                                                  |
     |   ,FD = fuzzy find directory                                              |
     |   ,FL = fuzzy find in lines                                               |
     |   ,FB = fuzzy find buffers                                                |
     |   ,FR = fuzzy find refresh files                                          |
     |   ,p = go to previous file                                                |
     |   ,t = toogle taglist                                                     |
     |                                                                           |
     |   ,h = new horizontal window                                              |
     |   ,v = new vertical window                                                |
     |                                                                           |
     |   ,i = toggle invisibles                                                  |
     |                                                                           |
     |   enter and shift-enter = adds a new line after/before the current line   |
     |                                                                           |
     |   :call Tabstyle_tabs = set tab to real tabs                              |
     |   :call Tabstyle_spaces = set tab to 2 spaces                             |
     |                                                                           |
     | Put machine/user specific settings in ~/.vimrc.local                      |
     -----------------------------------------------------------------------------  



# Keyboard Layout

I use english keyboard layout since is the most efficient layout for development.
Also I use the Caps Lock key as control key. 


# Wish List

Things i want to include, build, improve, etc

* Git grep inside vim 
* mvim should open a new tab and pwd should be set to the current file
* running 'gvim' or 'gvim .' should open the NERDTREE by default and an empty window on the right


# Enjoy!

![Vim for Rails in acction](http://dl.dropbox.com/u/56777664/Pantallazo%20del%202012-01-11%2022%3A42%3A27.png)

## And don't forget this!!

This Vim for Rails config files, are forked from [Federico Ramallo's](https://github.com/framallo) github account, so you can follow him, and get some awsome and usefull stuff... :)
