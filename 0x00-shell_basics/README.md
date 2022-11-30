# Explaining the files

This is a basic explanation of what each script in each file does. Below is a list of the individual files:

* [0-current_working_directory](#0-current_working_directory)
* [1-listit](#1-listit)
* [2-bring_me_home](#2-bring_me_home)
* [3-listfiles](#3-listfiles)
* [4-listmorefiles](#4-listmorefiles)
* [5-listfilesdigitonly](#5-listfilesdigitonly)
* [6-firstdirectory](#6-firstdirectory)
* [7-movethatfile](#7-movethatfile)
* [8-firstdelete](#8-firstdelete)
* [9-firstdirdeletion](#9-firstdirdeletion)
* [10-back](#10-back)
* [11-lists](#11-lists)
* [12-file_type](#12-file_type)
* [13-symbolic_link](#13-symbolic_link)
* [14-copy_html](#14-copy_html)
* [100-lets_move](#100-lets_move)
* [101-clean_emacs](#101-clean_emacs)
* [102-tree](#102-tree)
* [103-commas](#103-commas)


## 0-current_working_directory

This script prints the absolute path name of the current working directory

## 1-listit

This displays the contents of the current directory

## 2-bring_me_home

This changes the working directory to the user's home directory without use of any shell variable

## 3-listfiles

This displays the current directory contents in a long format

## 4-listmorefiles

This displays the current directory contents, including hidden files

## 5-listfilesdigitonly

This displays files in the long format but with user and group IDs displayed numerically

## 6-firstdirectory

This creates a directory "my_first_directory" in the /tmp/ directory

## 7-movethatfile

This moves the file "betty" from the /tmp/ to /tmp/my_first_directory

## 8-firstdelete

This deletes the "betty" file created from previous script

## 9-firstdirdeletion

This deletes the directory "my_first_directory" from the /tmp directory

## 10-back

This changes the working directory to the previous one

## 11-lists

This shows a long list of the current directory, the parent directory of the workind directory and the /boot directory. This includes all hidden files

## 12-file_type

This prints the type of file "iamafile" is. This file is found in the /tmp directory

## 13-symbolic_link

This creates a symbolic link to "/bin/ls" named __ls__. The link is created in the present working directory

## 14-copy_html

This copies all the HTML files from the current working directory to the parent of the working directory. It only copies files that didn't exist in the parent of the working directoryor were newer than the version in the parent of the working directory

## 100-lets_move

This moves all the files beginning with an uppercase letter to the directory /tmp/u

## 101-clean_emacs

This deletes all files in the current working directory that end with the character ~

## 102-tree

This creates 3 files in the current directory

## 103-commas

This lists all the files and directories seperated by commas with the digits coming first, all with hidden files showing
