## chnage in word
```sh
ciw
```
## replay the previous commnand
```sh
  .
```
## chnaging the world
```sh
:%s/currentword/replacerword/g   => g for global
:%s/currentword/replacerword/gc  => you will change with confirmation loop through all word and ask you (yes=y or no=n)
```

## visual or select in word
```sh
viw
```
## copy or yunk
```sh
y  => yunk = copy
p => Past
```
## see the registered commands
```sh
:reg
```
## if you want past third 3 register
```sh
"3p
```

## if you want to copy some text to x register
```sh
v   => for select then select the wanted text to be registered
"7y
```

## delete or remove text
```sh
v => and select it
d => selete it
```

## copy to system clip board
```sh
v => select
"+y
```

## past the working file name
```sh
"+%+p
```
## copy the working file name to systme clip board
```sh
:let @+=@%
```
## duplicate the current line
```sh
yyp
```
## moving
```sh
w Move one word to the right
b Move one word to the left
```
## delete current line
```sh
dd
```
## toggle terminal in neovim 
```sh
ctrl+shift+-  => ctrl+_
```

## in neotree plugin
```sh
?   => to see all the available commands there 🍝
a   => to add file or folder (folder end with /)
d   => delete options(y/n)
r   => rename
i   => file details
H   => toggle hidden files
```
## default installed neovim is lazyvim
## to toggle Neotree
## ⌨️ 'espace' is <leader> key 

```sh
,leader, fc => find file withsearch
,leader, e  => toggle neotree

U = redo/undo

ALT+J  = shift line DOWN
ALT+K  = shift line UP

$ = move the cursor to the end of the line
0 = move ################# start #######
gcc = comment and uncomment
```










