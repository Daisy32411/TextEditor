# KILO

**Kilo** - is a minimalistic text editor written in the C language. It works in the terminal and is inspired by editors like nano and vim. The entire source code is contained in a single file `kilo.c'.

Usage: `<./kilo filename>`

**HELPS:**

>CTRL-S: Save
>
>CTRL-Q: Quit
>
>CTRL-F: Find string in file (ESC to exit search, arrows to navigate)

## 🧠 Main topics
+ Processing input from the terminal
+ Configuring the terminal in raw mode
+ Working with buffers, lines, and screens
+ ANSI escape sequences
+ Minimalistic architecture of the editor

## 📂 Structure
> kilo.c      - the main source file of the editor
> 
> Makefile    - makefile for building and compiling a project


## 📚 Source
This project is based on the guide Salvatore Sanfilippo

[Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/)
