---
Name: Christian Torres
Semester: Fall 2023
Course: CIS 106
---

# Week Report 8

## What is VIM?
* VIM is a command-line text editor. VIM is a text editor that is not Included in Ubuntu and to install it, you use the command `sudo apt install vim`.

## What is nano?
* Nano is a very quick and efficient text editor that one can use while exploring the file system by using a terminal in Linux to have the advantage to stay on the terminal and making it easy to edit files.

## Starting and quitting VIM
* In order to start VIM type `vim`.
* In order to quit VIM press the esc key and type `:qa!`

## Different VIM modes
* Insert mode is the mode used for writing text or as the name says inserting text.
* Normal mode is the mode used for controlling and handling text.
* The command mode is used for entering vim commands.
* Visual mode is used for the navigation and manipulation of text selections.
* Select mode is similar to visual mode as it navigates and manipulates text as well.
* Ex-mode is similar to command-line mode but but is specifically used for batch processing.

## Insert text in VIM
* You can create a file and open vim at the same time by typing vim then a file name. 
  * Example: `vim futbol.txt`
* To insert text, you have to be in insert mode. In insert you can also use the arrow keys to move around, the enter key to continue typing in the next line, and backspace to delete text.

## Save a file in VIM
* In order to save a file in vim you will have to use this command after using the esc key and then inserting this command: `:w`.

## Search for a word inside VIM
* To search for words in vim insert: `/word` to search forward. And insert `?hello` to search backwards. 
* Use `*` to search for the next occurrence of the word under the cursor.
* Use `#` to search for the previous occurrence of the word under the cursor.

## Delete text in VIM
* To delete text in vim:
* Use `dw` to delete current word.
* Use `dd` to delete line under the cursor.
* Use `d + /word` to delete until the word given.