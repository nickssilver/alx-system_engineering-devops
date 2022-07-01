# 0x00. Shell, basics:
# An introductory project to the Bourne-again Shell.

# Scrpit Descriptions:
0-current_working_directory - prints the absolute path name of the current working directory.

1-listit - displays the contents list of the current directory.

2-bring_me_home - changes the working directory to the user's home directory.

3-listfiles - displays the current directory contents in long format.

4-listmorefiles - displays the current directory contents, including hidden files (starting with .) using the long format.

5-listfilesdigitonly - displays the current directory contents, including hidden files, in long format with the user and group IDs displayed numerically.

6-firstdirectory - creates a directory named holberton in the /tmp/ directory.

7-movethatfile - moves the file betty from /tmp/ to /tmp/holberton.

8-firstdelete - deletes the file betty in /tmp/holberton.

9-firstdirdeletion - deletes the directory holberton in the /tmp/ directory.

10-back - changes the working directory to the previous one.

11-lists - lists all files, even ones that are normally hidden, in long format that are in the current directory, the parent of the current directory, and the /boot/ directory, in that order.

12-file_type - prints the type of the file named iamafile.

13-symbolic_link - creates a symbolic link to /bin/ls named __ls__, which is in the current working directory.

14-copy_html - copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

15-lets_move - moves all files beginning with an uppercase letter to the directory /tmp/u.

16-clean_emacs - deletes all files in the current working directory that end with the character ~.

17-tree - creates the directories welcome/, welcome/to/, and welcome/to/holberton/ in the current directory with less than two spaces in the script.

18-commas - lists all the files and directories of the current directory separated by commas with the specifications that:

directory namaes should end with a slash
files and directories starting with a dot should be listed
the listings should be alpha ordered, except for the directories . and .. which should be listed at the very beginning,
only digits and letters are used to sort; Digits should come first
the listing should end with a new line
holberton.mgc - can be used with the command file to detect Holberton data files, which always contain the string HOLBERTON at offset 0.
