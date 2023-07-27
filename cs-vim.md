# Vim Cheat Sheet

## Navigation
- `h`: Move cursor left
- `j`: Move cursor down
- `k`: Move cursor up
- `l`: Move cursor right
- `w`: Move forward one word
- `b`: Move backward one word
- `0`: Move to the beginning of the line
- `^`: Move to the first non-blank character of the line
- `$`: Move to the end of the line
- `gg`: Move to the first line of the document
- `G`: Move to the last line of the document
- `<line number> G`: Move to a specific line number

## Editing
- `i`: Insert mode (insert text before the cursor)
- `a`: Append mode (insert text after the cursor)
- `A`: Append mode at the end of the line
- `o`: Open a new line below the current line
- `O`: Open a new line above the current line
- `x`: Delete the character under the cursor
- `dd`: Delete the current line
- `yy`: Yank (copy) the current line
- `p`: Paste the yanked or deleted text after the cursor
- `P`: Paste the yanked or deleted text before the cursor
- `u`: Undo the last change
- `Ctrl + r`: Redo the undone change

## Searching and Replacing
- `/`: Search forward
- `?`: Search backward
- `n`: Move to the next search result
- `N`: Move to the previous search result
- `:%s/old/new/g`: Replace all occurrences of 'old' with 'new' in the whole file

## Saving and Exiting
- `:w`: Save the file (write)
- `:q`: Quit Vim
- `:wq` or `ZZ`: Save and quit
- `:q!`: Quit without saving (force quit)

## Modes
- `Esc`: Return to normal mode from any other mode
- `v`: Enter visual mode (character-wise selection)
- `V`: Enter visual mode (line-wise selection)
- `Ctrl + v`: Enter visual block mode (block-wise selection)
- `:`: Enter command-line mode

## Miscellaneous
- `.`: Repeat the last command
- `Ctrl + g`: Show current file information and position
- `Ctrl + o`: Jump back to the previous location
- `Ctrl + i`: Jump forward to the next location
- `:set nu`: Show line numbers
- `:set nonu`: Hide line numbers
- `:help <command>`: Open Vim's built-in help for a specific command
