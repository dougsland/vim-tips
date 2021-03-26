- [vim-tips](#vim-tips)
  * [To paste code](#to-paste-code)
    + [Set paste mode](#set-paste-mode)
    + [Disable paste mode:](#disable-paste-mode-)
    + [Set a keyboard key to pastemode](#set-a-keyboard-key-to-pastemode)
    + [Show when insert mode is set](#Show-when-insert-mode-is-set)
    + [Do not highlight searched words](#Do-not-highlight-searched-words)
    + [Autoindent](#Autoindent)
    + [Set Tab](#Set-Tab)
    + [Convert tabs to spaces](#Convert-tabs-to-spaces)
    + [Turn on syntax highlighting](#Turn-on-syntax-highlighting)

# vim-tips
Just another notes from VIM

## Turn on syntax highlighting
No need to use the set word, just syntax on
```
:syntax on
```

## Set Tab
Sets a tab to be four spaces
```
:set tabstop=4
```

## Convert tabs to spaces
```
:set expandtab
```
## Autoindent
```
:set autoindent
```

## Do not highlight searched words
```
:set nohlsearch
```

## Show when insert mode is set
```
:set showmode
```
## To paste code
### Set paste mode
```
:set paste
```

### Disable paste mode:
```
:set nopaste
```

### Set a keyboard key (F2) to pastemode
```
$ ~/.vimrc
set pastetoggle=<F2>
```
