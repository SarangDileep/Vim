# Vim

> vim is a very light and easily costomizable editor



# Basic commands:

`i` 
___
Enter insert mode

`a` 
___
append

`:q` -quit

`:wq` -save and quit

`h` -left

`l`-right

`j`-down

`k`-up

`shift+i` -insert at begining of the line

`shift+a` -insert at end of line

`$` -move to end of a line

`^` -move to begining of a line

`v`   -visually select

`x` -delete the character pointed by the cursor

`shift+v` -visually select a block

`c` -change(Delete and enter into insert mode)

`ci` -change in (eg:-'ci(' changes everything inside the brackets)

`ciw` -change in a word(the cursor can be anywhere on the word)

`ca`  -change and (eg:-'ca(' Deletes everything inside the brackets along with the bracket and enters insert mode)

`c$` -change till end(from cursor point)

`dd` -Delete a line

`diw` -Delete in a word

`di` -Delete in

`da` -Delete and

`d$` -delete till end(from the cursor position)

`y` -yank

`*y` -yank such that u can paste it even outside vim

`?word` -searches the word in file

`:vsplit` -Vertical split

`:split` -Horizontal split

`ctrl+n` -autocompletion option


# command combos:

`Shift+v,y` -yank selected text

`:%s/old/new/g` -replace old with new in the entire file

`10j` -move 10 times down(you can replace 10 with any number and j with other motions(h,k,l))
