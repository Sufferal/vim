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
- `r` - Replace character under the cursor

#### Search
- `/` - Search forward
  - `n` - Move to the next search result
  - `N` - Move to the previous search result
- `?` - Search backward, now `n` and `N` will move in the opposite direction
- `*` - Search for the word under the cursor
- `#` - Search for the word under the cursor in the opposite direction

#### Vertical Movement
- `{` - Move to the start of the paragraph
- `}` - Move to the end of the paragraph
- `gg` - Move to the start of the file
- `G` - Move to the end of the file

### Insert Mode
- `i` - Insert text before the cursor
- `I` - Insert text at the start of the line
- `a` - Insert text after the cursor
- `A` - Insert text at the end of the line
- `o` - Insert text on the next line
- `O` - Insert text on the previous line
- `Esc` or `Ctrl + C` - Exit insert mode

### Command-line Mode
- `:` - Enter command-line mode
- `:5` - Move to line 5

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

## Position 
- `_` - Move to the first non-blank character of the line (similar to `0`, but ignores whitespace)
- `$` - Move to the end of the line
- `0` - Move to the start of the line
- `f` - Move to the next occurrence of a character. For example, `fa` moves to the next 'a' character.
- `F` - Move to the previous occurrence of a character
- `t` - Move to the character before the next occurrence of a character
- `T` - Move to the character after the previous occurrence of a character
- `,` - Repeat the last `f`, `t`, `F`, or `T` command in the opposite direction
- `;` - Repeat the last `f`, `t`, `F`, or `T` command in the same direction

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