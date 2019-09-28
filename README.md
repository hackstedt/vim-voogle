voogle.vim
============

A simple small plugin to help you google from vim but not display
the results in a buffer. (it's 2013)

... It's 2019 already. Here is my own twist on it.

##Install

The Same as with many other vim plugins.

##Usage

The shortcut is `gs`
You can google for the word under the cursor in normal mode,

or you can search for selected text in visual mode.

Voogle.vim tries to find an available browser from:

* Vivaldi
* Chrome/Chromium
* Firefox
* links

##Options

Set the `g:search_engine` variable to your desire for custom searches
if you don't like google
Default: let g:search_engine = "https://google.com/search?q="

You can disable the plugin by `let g:loaded_voogle=0`.

" Use this to set a custom mapping
Default:  let g:voogle_map = "gs"

##License

Distributed under the same terms as Vim itself. See `:help license`.
