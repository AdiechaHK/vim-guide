# vim-guide
Just Vim commands for my referance.


## Modes

There are 3 modes in vim editor

* normal mode (by default you will be in this mode, when you are in insert mode or visual mode press `esc` to get back to normal mode)
* insert mode (type `i` to enter in this mode, you can type `a` (append) to enter in insert mode and cursor at the end of the line)
* visual mode (type `v` to enter in this mode)

## Moving Cursor

* h (left)
* j (down)
* k (up)
* l (right)
* G (to bottom of the file)
* gg (to top of the file)

## commands

it will be combination of `action` and `item`

* achtions can be
  - delete `d` (`dd` to delete line)
  - replace `r`
  - change `c` (`cc` to chagne line)
  - copy `y` (you can paste by pressing `p`)

* item can be 
  - word `w`
  - line `l`
  - till end of the line `$`
  - till end of the current word `e`
