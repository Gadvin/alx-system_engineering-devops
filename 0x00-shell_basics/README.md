#!/bin/bash
This is a respository to answer the shell questions

Question 0. Where am I?
This question is to Write a script that prints the absolute path name of the current working directory
Script file : 0-current_working_directory

Question 1. What’s in there?
This question is to Display the contents list of your current directory.
Script file : 1-listit

Question 2. There is no place like home
This question is to Write a script that changes the working directory to the user’s home directory.
Script file : 2-bring_me_home

Question 3. The long format
This question is to Display current directory contents in a long format
Script file : 3-listfiles

Question 4. Hidden files
This question is to Display current directory contents, including hidden files (starting with .). Use the long format.
Script file : 4-listmorefiles

Question 5. I love numbers
This question is to Display current directory contents.

Long format
with user and group IDs displayed numerically
And hidden files (starting with .)

Script file : 5-listfilesdigitonly

Question 6. Welcome
This question is to Create a script that creates a directory named my_first_directory in the /tmp/ directory.
Script file : 6-firstdirectory

Question 7. Betty in my first directory
This question is to Move the file betty from /tmp/ to /tmp/my_first_directory
Script file : 7-movethatfile

Question 8. Bye bye Betty
This question is to Delete the file betty.

The file betty is in /tmp/my_first_directory
Script file :  8-firstdelete

Question 9. Bye bye My first directory
This question is to Delete the directory my_first_directory that is in the /tmp directory.
Script file : 9-firstdirdeletion

Question 10. Back to the future
This question is to Write a script that changes the working directory to the previous one.
Script file : 10-back

Question 11. Lists
This question is to Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
Script file : 11-lists

Question 12. File type
This question is to Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
Script file : 12-file_type

Question 13. We are symbols, and inhabit symbols
Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
Script file : 13-symbolic_link

Question 14. Copy HTML files
This question is to Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

You can consider that all HTML files have the extension .html
Script file : 14-copy_html

Question 15. Let’s move
This question is to Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

You can assume that the directory /tmp/u will exist when we will run your script
Script file : 100-lets_move

Question 16. Clean Emacs
This question is to Create a script that deletes all files in the current working directory that end with the character ~.
Script file : 101-clean_emacs

Question 17. Tree
This question is to Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

You are only allowed to use two spaces (and lines) in your script, not more.
Script file : 102-tree

Question 18. Life is a series of commas, not periods
This question is to Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line

Script file : 103-commas

Question 19. File type: School
This question is to Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
Script file : school.mgc
