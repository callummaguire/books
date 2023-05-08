## Navigation

This chapter of the book introduces all the concepts related to navigating in the Linux system.

### Commands

- `pwd`: Displays the current working directory. This command is used in scripts to understand where the user is running the script.

- `ls`: Lists the contents of the current directory.

- `cd`: Changes the current directory to the one specified in the file path.

- `~`: gives the home directory as the starting instances. for example, cd ~/home.

 
Absolute pathnames are paths that begin at the root directory and follow the tree from branch to branch. An example of an absolute pathname is `/usr/bin`.

In contrast, relative pathnames are paths that start in the working directory. They use special notations like `.` or `../` to navigate the file system. The `.` symbol represents the current working directory, while `../` means to navigate up to the parent directory and continue navigation from there.

Directories are represented as a tree data structure in the Linux file system.

filenames are case senstive and can have symbol inside them, always use the underscore as a subsitute for spacing between words in filename.

linux operating system has no concept of file extension. it is based on what you are using to open up the file. 

hidden files start with . and needs ls -a to show up in the command line


