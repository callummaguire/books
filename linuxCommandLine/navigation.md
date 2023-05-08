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

## Exploring the system

### Commands

- `file`: gives us the file type of the filename given.
- `less`: it gives a page by page reader for text files in ascii format. less is the successor to the more command as it allows for the user to go back and forth on pages.

### Folders and their uses

- `/`: the root directory where all files are encompassed.
- `/user`: it contains all the programs and support files used by regular users.
- `/etc`: contains all the system-wide configuration like `/etc/crontable` that defines when automated jobs are run.

There are plenty more folders that could be explained, but these were a few of the cool ones.

### Concepts

Symbolic links are defined by `->` when showing the `ls` command. Think of symbolic links as a way of doing linked lists in the folder structure. This can be useful if you want a parent file to change a child file at the same time. The real-world use could be publishing software. Let's say you have a `lib.exe` and want to publish a new `lib.exe` because it has new code. We can make a `lib_1.exe` which has all the new code and point a symbolic link from `lib.exe` to `lib_1.exe`.

Hard Links is the alternative
  