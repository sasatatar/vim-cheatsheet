
key         | description
------------|----------------------
gg          | go to top of document
G           | go to bottom of document
{           | go up block of code
}           | go down block of code
dd          | delete line and copy it to clipboard
u           | undo
ctrl + R    | redo
.           | repeat last command
y           | copy selection to clipboard
yy          | copy line
p           | paste below
P           | paste above
V           | enter Visual mode
o           | add new line below and enter Insert mode
O           | add new line above and enter Insert mode
d}          | delete from cursor to the end of the block of code
%           | toggle between braces/bracket pairs () | {} | []
d%          | delete everything from cursor to the first closing brace
c           | enter change
cw          | change word
D           | delete from cursor to rest of line
C           | delete rest of line and enter insert mode
ct}         | change from cursor to `}` (keeps `}`)
;           | next instance
zz          | center view around cursor
~           | swap the case of the character
r           | replace character under cursor with another character
R           | enters insert mode (replaces characters as you type)
<br>

## Horizontal movement

key         | description
------------|-------------------------
w           | move to next word
b           | move to previous word
W           | move to next space delimited segment
B           | move to previous space delimited segment
:[n]        | go to line number `n`
^           | go to first word in line
0w          | go to first word in line
0           | go to beginning of line
$           | go to end of line
t[c]        | go to character (places cursor before the character)
f[c]        | go to character (places cursor at the character)
a           | append
A           | append at the end of the line
x           | delete marked character
I           | move cursor to the line beginning and enter insert mode