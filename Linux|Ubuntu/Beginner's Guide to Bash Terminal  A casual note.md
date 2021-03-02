# Beginner's Guide to Bash Terminal : A casual note

## File system

1. ls 
2. ls -a : list all files
3. `file [filename]` tells you what kind of file it is
4. `locate [filename]` to find the path of a file that contains the certain name
5. `which [commandname]` to  tell if a command/application is installed

`history` list everything user has typed in

## To Get Help

1. `whatis [commandname]` shows a simple description of the command's function
2. `apropos [something you wanna do]` shows  every command relates to the very thing you wanna do.
3. `man [commandname]` the manual page for a command

## File Directory Operation

1. `mkdir [directory name]...` 

2. `touch [filename]` If the file exists: do nothing but update the time of last change; if the file doesn't exist: creates the file with nothing in it.

3. `cp ...` copy something. To do complicated work, add options.

4. `mv ...`   rename or move 

5. `rm` delete a file , cannot retrive

   for single file : FILENAME* (remove everything contains "FILENAME")

   for folders: rm -r ... (dir name)

   `rmdir` remove empty directory

6. `cat [filename]` print the file content 

   `cat >> [filename]`

## Edit&Scan File content

1. `more` & `less`
2. `nano`
3. 

