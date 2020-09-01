# Vim

vim is a very light and easily costomizable editor



# Basic commands:

i  -Enter insert mode

a -append

:q -quit

:wq -save and quit

h -left

l-right

j-down

k-up

shift+i -insert at begining of the line

shift+a -insert at end of line

$ -move to end of a line

^ -move to begining of a line

v   -visually select

x -delete the character pointed by the cursor

gg-move to begining of file

shift+g -move to end of file

shift+h -move to top

shift+m -move to middle

shift+l -move to bottom

w -move to next word

b-move to previous word

e-move to end of a word

shift+v -visually select a block

c -change(Delete and enter into insert mode)

ci -change in (eg:-'ci(' changes everything inside the brackets)

ciw -change in a word(the cursor can be anywhere on the word)

ca  -change and (eg:-'ca(' Deletes everything inside the brackets along with the bracket and enters insert mode)

c$ -change till end(from cursor point)

dd -Delete a line

diw -Delete in a word

di -Delete in

da -Delete and

d$-delete till end(from the cursor position)

u-undo

y -yank

*y -yank such that u can paste it even outside vim

?word -searches the word in file

:vsplit -Vertical split

:split -Horizontal split

:earlier 10s -takes to how the file was earlier 10 sec ago(give m for minutes)

ctrl+n -autocompletion option


# command combos:

Shift+v,y -yank selected text

10j -move 10 times down(you can replace 10 with any number and j with other motions(h,k,l))

3w -move 3 words

d3w -deletes 3 word

c3w - change 3 words

d+shift+g -delete till end of file from the cursor point

d+gg -delete till start of file from cursor point

# Advanced commands

:r!command -run a linux command within vim

:term -open terminal from within vim

:%s/old/new/g -replace old with new in the entire file
