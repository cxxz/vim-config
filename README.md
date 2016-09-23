---
Title: Bill's Customized Vim Configuration
Created:  2016 Sep 23

---

Solarized Colorscheme for Vim
=============================

Developed by Ethan Schoonover <es@ethanschoonover.com>

Installation
------------

### Colorscheme installation

1.  Move `solarized.vim` to your `.vim/colors` directory:

        $ mv solarized.vim ~/.vim/colors/

### Vimrc File

        $ mv vimrc ~/.vimrc

Put the following two lines in your .vimrc:

    syntax enable
    set background=dark
    colorscheme solarized

or, for the light background mode of Solarized:

    syntax enable
    set background=light
    colorscheme solarized

