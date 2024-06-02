## Vim - vimtutor short notes

### 1.1 Moving the cursor  
h for left  
k  for up  
l for right  
j for bottom   

### 1.2 Exiting the vim  
:q! to exit without saving

### 1.3 Deleting the char  
x to delete the character under the cursor

### 1.4 Insert mode  
i to enter insert mode

### 1.5 Appending
A to move cursor at the end of the line and append it

### 1.6 Save and Exit  
:wq to save the file and exit

### 2.1 Delete a word
dw to delete a word until the start of the next word  
de to delete a word until the end of the current word

### 2.2 Delete to the end of the line
d$ to delete from cursor to the end of the line

### 2.3 Operators and motions
In above examples d is the operator and e, w and $ are the motions

### 2.4 Using the count for the motion
2w to move the cursor 2 time forward  
3e to move the cursor to the end of the third word  
4b to move the cursor 4 time backward  
0 to move the cursor at the start of the line  
> Note: 2, 3 and 0 are the count here

### 2.5 Using count to delete more
d2w to delete 2 words

### 2.6 Delete a whole line
dd to delete a line

### 2.7 Undo command
u to undo the last command  
U to fix a whole line  
ctrl-r to redo the commands

### 3.1 Put command
p to put the line stored in vim registered  
> You can paste the line after dd or y using p command

### 3.2 Replace command
rx to replace the cursor with x

### 3.3 Change operator
ce to change the word  
cw to change the word untill the start of teh next word  
c$ to change untill teh end of the line  
cc to change the whole line  

### 4.1 Cursor location and file status
ctrl-G to show the location of the cursor  
G to move to the bottom of the file  
gg to move to the top of the file  
xxG to move to line number xx

### 4.2 Search command
/xxxx to search "xxxx" in the file  
n to move to the next occurance  
N to move to the previous occurance  
? to search from bottom to top  
ctrl-o to go back to where you came from

### 4.3 Matching parentheses search
% place the cursor on bracket and type % to move to the matching bracket  

### 4.3 Substitute command
:s/old/new/g to substitute replace old with new, g is global flag  
:s/old/new only changes first occurrence  
:s/old/new/gc to change all the occurrence with a prompt  
:#,#
