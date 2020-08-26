# VIM - Text Editor

## Getting Started

Basically vim has different modes

1. Normal mode
2. Insert mode
3. Command Line
4. Visual mode

These are some of the basic mode to work with file. You will learn to switch between them and how to use them in the following topics.

## Create or Open file

To open a file in vim, type the following command in bash

```bash
vim file.txt
```

It will open a file.txt in vim editor if file already exist or create new one.

## Switch between modes

It always start with Noraml mode. To switch to any other mode you must be in normal mode.<br>
You can use **ESC** key to switch to Normal mode from any modes.<br>
By using **i** key from normal mode you can enter into insert mode.<br>
By using **:** key from normal mode you can enter into command line.<br>
By using **v** key from normal mode you can enter into visual mode.

## Insert mode

Once you get into insert mode you can type anything you want. Use **ESC** to switch normal mode.

## Close file

To close file you have to switch command line mode. 
* **:q!** - to close file without saving
* **:wq** or **x!** - to save and close file
* **:w** to save file
* **:w** filename to save as feature

## Navigation inside file

From command line
* **:set number** - command will set number to each line of file
* **:<number_of_line>** - command will switch to specific line you enter (e.g) :4 switch to line 4
* **:$** - switch to last line

From normal mode
* **$** - to reach end of line
* **gg** - to top of file
* use **arrow key** to move
* **l** - move left
* **h** - move right
* **j** - move down
* **k** - move up

## Editing file

From normal mode
* **dd** - delete a line
* **x** - backward delete character
* **u** - UNDO
* **p** - duplicate a line
* **o** - create a new line and enter into insert mode

### Copy and Paste

From visual mode
* **v** - move to visual mode
* **arrow keys** - by using navigation select portion you want to copy
* **y** - copy a file (YANK)

From normal mode
* **p** - paste a copied text

## Searching

From command line
* **:/<Search_word>** - to search for specific word in file (e.g) **:/Hello** will select all Hello in file
* **n** - to switch between searched words act as **Next**

## Split window

From command line
* **:split filename** - split the window horizontally with the new file
* **ctrl + ww** - to switch between files

## Color scheme

From command line
* **:colorscheme** - to see the colorscheme currently in
* **:colorscheme + space + tab** - to list all available colorscheme
* **:colorscheme <name_of_scheme>** - to switch or set other scheme

# Links
[Getting started with VIM](https://opensource.com/article/19/3/getting-started-vim)

