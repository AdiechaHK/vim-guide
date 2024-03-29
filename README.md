# vim-guide
Just Vim commands for my referance.


## Modes

There are 3 modes in vim editor

* normal mode (by default you will be in this mode, when you are in insert mode or visual mode press `esc` to get back to normal mode)
* insert mode (type `i` to enter in this mode, you can type `a` (append) to enter in insert mode and cursor at the end of the line)
* visual mode (type `v` to enter in this mode)

## Moving Cursor

* `h` (left)
* `j` (down)
* `k` (up)
* `l` (right)
* `G` (to bottom of the file)
* `gg` (to top of the file)

## Commands

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

## Working with multiple files

* `vim .` to open current directory in vim
* Select any file it will open right there
* `:e filename` to change file in currect tab
* `CTRL + W` to chagne one tab to another
* `:q` will close tab, it will close vim if single tab is open there
* `sp` to split vertically
* `vs` to split horizontally
* Change tab size
  - `Ctrl+w` `=` to make all tab occupy equal amount of space
  - `20` `Ctrl+w` `_` set hight to 20
  - `30` `Ctrl+w` `|` set width to 30


## Special cases

* go to line number `:<line_number><enter>` example `:34⏎`
* remove paragraph `d}`
* apply tab to next 4 lines `4<shift><dot>`, dot => `.`
* move by block `}` => forward, `{` => backword
* move back word by word: `b`
* copy 10 lines `10yy` -> this will copy 10 lines from current cursor position
* copy block `y}`, copy block from middle of the block `{y}` (basically `{` will move cursor to the starting of the block and then `y}` will copy the whole block)
* Use terminal inside vim `:term`
* comment multiple lines
  - `Ctrl+v` - visual mode
  - `<number>j` - to select n number of lines 
  - `Shift+i` - move to insert mode
  - `#` - to add hash (`#`) for comment
  - `d` or `x` to delete comment
  - `Esc+Esc` to leave out
* Multiline indentation
  - `Ctrl+v` - visual mode
  - `5j` - select next 5 lines
  - `>` for add indentation, `<` for remove indentation (de-indent)
