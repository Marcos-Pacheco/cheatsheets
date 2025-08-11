#lvim cheatsheet

# -> means then (Ex.: ctrl+r -> + means 'press ctrl+r together, then +)

# open current folder
lvim .

# open file explorer
space+e

# switch between explorer and files
ctrl+h # goes left
ctrl+l # goes right

# search file
space+f

# search inside file
/

# copy selection
v # enter character-wise selection
# make the selection
y # yank the selection
# move where to copy
p # paste
# if in a gui window of lvim
ctrl+r -> +

# undo
esc # enter command mode
:u

# visual wrap text
:set wrap # activates
:set nowrap # deactivates

# start an instance of terminal inside lvim
:term

# init a terminal with lazygit
:term lazygit

# create folder
space -> e # enter explorer mode
A

# create file
space -> e # enter explorer mode
A

# enter lazygit
space -> g -> g

# quit lazygit
ctrl+c
