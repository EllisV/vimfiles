Installation
============

* Clone the repo: `git clone https://github.com/EllisV/vimfiles.git ~/.vim`
* Run: `make first-install`

Requirements
============

* Vim 7.3.885+ compiled with [if\_lua](http://vimdoc.sourceforge.net/htmldoc/if_lua.html). To check if your VIM has lua type in `:echo has("lua")`
* [silversearcher-ag](https://github.com/ggreer/the_silver_searcher)
* [FZF](https://github.com/junegunn/fzf)
* Python
* Eclipse Mars (if you want to use Eclim)
* `instant-markdown-d`. Install it with `npm install -g instant-markdown-d`


## Debian (or Ubuntu)

Make sure you have any of these packages:
* vim-nox
* vim-gtk
* vim-gnome
* vim-athena

For installing silversearcher-ag use `sudo apt-get install silversearcher-ag`

## Mac OS X

    brew install macvim --with-cscope --with-lua --HEAD
    brew install the_silver_searcher
