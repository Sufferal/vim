# Vim Cheatsheet
This is a cheatsheet for Vim commands and shortcuts.

Note: I'm using Vim [extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) for Visual Studio Code.

## Theory
There is CCM (Command, Count, Motion) pattern in Vim. 
- **Command**: What you want to do.
- **Count**: How many times you want to do it.
- **Motion**: Where you want to do it.

For example, `3j` means move down 3 lines or `d3j` means delete 3 lines down.

## Modes 
- **Normal mode**: The mode you start in and the mode you return to after you've finished typing text.
- **Insert mode**: The mode you use to type text into the file.
- **Visual mode**: The mode you use to select text.
- **Command-line mode**: The mode you use to save, exit, and perform other operations.

### Normal Mode
- `i` - Insert mode
- `v` - Visual mode
- `V` - Start visual line mode (selects whole lines)
- `p` - Paste after cursor
- `P` - Paste before cursor
- `x` - Delete character under the cursor

### Insert Mode
- `i` - Insert text before the cursor
- `a` - Insert text after the cursor
- `o` - Insert text on the next line
- `O` - Insert text on the previous line
- `Esc` or `Ctrl + C` - Exit insert mode

## Navigation
### Basic
- `h` - Move cursor left
- `j` - Move cursor down
- `k` - Move cursor up  
- `l` - Move cursor right

### Words
- `w` - Move to the start of the next word
- `e` - Move to the end of the next word
- `b` - Move to the start of the previous word
- `ge` - Move to the end of the previous word

## Commands
- `d` - Delete
  - `dd` - Delete line
  - `dw` - Delete word 
- `y` - Yank (copy)
  - `yy` - Yank line
  - `yw` - Yank word

## History
- `u` - Undo
- `Ctrl + R` - Redo