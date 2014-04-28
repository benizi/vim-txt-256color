# vim-txt-256color

Dumb terminal-escapes-to-colors text syntax for Vim.

## Installation

If you don't already use an add-on manager for Vim, you
really should.  I prefer [Vundle](https://github.com/gmarik/vundle), but lots of
people seem to like [Pathogen](https://github.com/tpope/vim-pathogen).
Vim Addon Manager (VAM), has [a good comparison of vim addon managers](https://github.com/MarcWeber/vim-addon-manager/tree/master/doc/vim-addon-manager-additional-documentation.txt) (search for `VAM-comparison`).

With Vundle, add: `Bundle 'benizi/vim-txt-256color'` wherever you manage your
`Bundle` commands.

## Configuration

You can set: `g:txt_256color_settings` to a truthy value (e.g. `1`) to set up
conceal-related settings.

## Usage

Already, I've got two TODO items:

- Currently, you have to set this filetype manually.

```vim
:se ft=txt-256color
```

- It's not quite set up the way you're supposed to set up a filetype plugin.
(doesn't check for existing syntax, etc.).  Since it has to be done manually
anyway, presumably you want the syntax highlighting.
