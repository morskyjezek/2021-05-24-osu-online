---
layout: reference
title: Reference
---

## Shell Cheat Sheet
**[Source](https://librarycarpentry.org/lc-shell/reference)**
_____
### Shell: Navigation Basics

**`pwd`** - print working directory

**`man`** - display the user manual

**`ls`** - list contents of a directory

- `ls -l` - list file information
- `ls -lh` - list human readable file information
- `ls -F` - list files and directories (directories will have a trailing `/`)
- `ls -a` - list all files, including hidden files
- `ls *.txt` - list all files that end with `.txt`

**`cd`** change directory

  `cd pathname` - takes you to the directory specified by `pathname`
  
  `cd ~` -  takes you to your home directory
  
  `cd ..` - takes you up one directory

______
### Shell: Interacting with Files

**`mkdir`** make a directory

**`head`** output first 10 lines of a file or files

**`mv`** rename or move a file or files. Syntax for renaming a file: `mv FILENAME NEWFILENAME`

**`cp`** make a backup copy of a file or files. Syntax: `cp FILENAME NEWFILENAME`

**`touch`** will update timestamp information on files.
