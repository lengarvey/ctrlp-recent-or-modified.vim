# ctrlp-modified.vim

Easily open locally modified files or files that were modified in the last 2 commits in your git-versioned projects.
The idea is that you're likely to be editing the same files again, or maybe
you just want to catch up on the progress you've made after coming back from a break.

Based entirely off @jasoncodes ctrlp-modified.vim

## Installation

Add `ctrlp-recent-or-modified` after `ctrlp` in your [Vundle](https://github.com/gmarik/vundle) config:

``` vim
Bundle 'kien/ctrlp.vim'
Bundle 'lgarvey/ctrlp-recent-or-modified.vim'
```

Then set yourself up a mapping:

``` vim
map <Leader>m :CtrlPModified<CR>
```
