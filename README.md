# alx-system_engineering-devops
Project for Shell basics    
In this project, I will be working with the basic shell commands such as navigation, manipulation, and others.     
[TASK 0. Where am I?](./0x00-shell_basics/0-current_working_directory) - Write a script that prints the absolute path name of the current working directory.

[TASK 1. What’s in there?](./1-listit) - Display the contents list of your current directory.

[TASK 2. There is no place like home](./0x00-shell_basics/2-bring_me_home) - Write a script that changes the working directory to the user’s home directory.     
You are not allowed to use any shell variables

[TASK 3. The long format](./0x00-shell_basics/3-listfiles) - Display current directory contents in a long format

[TASK 4. Hidden files](./0x00-shell_basics/4-listmorefiles) - Display current directory contents, including hidden files (starting with .).       
Use the long format.

[TASK 5. I love numbers](./0x00-shell_basics/5-listfilesdigitonly) - Display current directory contents.         
Long format       
with user and group IDs displayed numerically        
And hidden files (starting with .)        

[TASK 6. Welcome](./0x00-shell_basics/6-firstdirectory) - Create a script that creates a directory named `my_first_directory` in the /tmp/ directory.

[TASK 7. Betty in my first directory](./0x00-shell_basics/7-movethatfile) - Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

[TASK 8. Bye bye Betty](./0x00-shell_basics/8-firstdelete) - Delete the file `betty`. The file `betty` is in `/tmp/my_first_directory`.

[TASK 9. Bye bye My first directory](./0x00-shell_basics/9-firstdirdeletion) - Delete the directory `my_first_directory` that is in the /tmp directory.

[TASK 10. Back to the future](./0x00-shell_basics/10-back) - Write a script that changes the working directory to the previous one.

[TASK 11. Lists](./0x00-shell_basics/11-lists) - Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.

[TASK 12. File type](./0x00-shell_basics/12-file_type) - Write a script that prints the type of the file named `iamafile`. The file iamafile will be in the /tmp directory when we will run your script.

[TASK 13. We are symbols, and inhabit symbols](./0x00-shell_basics/13-symbolic_link) - Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.

[TASK 14-copy_html](./0x00-shell_basics/14-copy_html) - Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension `.html`

[TASK 15. Let’s move](./0x00-shell_basics/15-lets_move) - Create a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`. You can assume that the directory /tmp/u will exist when we will run your script

[TASK 16. Clean Emacs](./0x00-shell_basics/16-clean_emacs) - Create a script that deletes all files in the current working directory that end with the character `~`.

[TASK 17. Tree](./0x00-shell_basics/17-tree) - Create a script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory. You are only allowed to use two spaces in your script, not more.

[TASK 18. Life is a series of commas, not periods](./0x00-shell_basics/18-commas) - Write a command that lists all the files and directories of the current directory, separated by commas (,).      
Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line.

[TASK 19. File type: School](./0x00-shell_basics/School.mgc) - Create a magic file `school.mgc` that can be used with the command `file` to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0.
