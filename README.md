# textutil.vim

This plugin allows one to open an RTF, RTFD, DOC, or WordML file as a plaintext
file, edit it, and save the result back into that respective format.

## Prerequisites

 - vim, of course
 - `textutil` command in MacOSx (10.4 or later)

## Installation

1. Copy `textutil.vim` into the vim plugin directory, e.g. `$HOME/.vim/plugin/`
2. Restart vim.

Note: See `:help add-plugin`, `:help add-global-plugin`, `:help runtimepath` to
      find out more about plugins.

## Configuration

When this script converts RTF, RTFD, DOC or WordML into plain text, it uses the
`textutil` command and the `g:textutil_txt_encoding` encoding. By default, this
is `utf-8`. To use other encodings, set `g:textutil_txt_encoding` in `vimrc`.

For example,

        :let g:textutil_txt_encoding='Shift_JIS'

This is a mirror of http://www.vim.org/scripts/script.php?script_id=1432
