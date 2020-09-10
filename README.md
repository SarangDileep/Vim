# Vim

> vim is a very light and easily customizable editor.

# Basic commands:

`i` 
___
Enter insert mode

`a` 
___
Append

## Exit

`:q` - Quit

`:wq` - Write/Save and quit

## Navigation

`h` - Left

`l`- Right

`j`- Down

`k`- Up

`$` - Move to end of a line

`^` - Move to begining of a line

## Insert

`shift+i` -  Insert at begining of the line

`shift+a` - Insert at end of line (append)

`c` - Change(Delete and enter into insert mode)

`ci` - Change in (eg:-'ci(' changes everything inside the brackets)

`ciw` - Change in a word(the cursor can be anywhere on the word)

`ca`  - Change and (eg:-'ca(' Deletes everything inside the brackets along with the bracket and enters insert mode)

`c$` - Change till end(from cursor point)

## Deleting

`x` - Delete the character pointed by the cursor

`dd` - Delete a line

`diw` - Delete in a word

`di` - Delete in

`da` - Delete and

`d$` - Delete till end(from the cursor position)

## Yanking and selecting

`y` - Yank

`*y` - Yank such that you can paste it even outside vim

`v` - Visually select (enters visual mode)

`shift+v` -  Visually select a block

## Others

`?word` - Searches the word in file

`:vsplit` - Vertical split

`:split` - Horizontal split

`ctrl+n` -  Autocompletion option


# Command combos:

`Shift+v,y` - yank selected text

`:%s/old/new/g` - replace old with new in the entire file

`:%s/old/new/gc` - replace old with new in the entire file, with a prompt asking you for confirmation for each word.

`10j` - move 10 times down(you can replace 10 with any number and j with other motions(h,k,l))
