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
4b to move the cursor 2 time backward  
0 to move the cursor at the start of the line  
> Note: 2, 3 and 0 are the count here

### 2.5 Using count to delete more
d2w to delete 2 words

### 2.6 Delete a whole line
dd to delete a line

### 2.7 Undo command
u to undo the last command  
U to fix a whole line
CTRL-r to redo the commands
