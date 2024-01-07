Using the Linux Command Line
1. The CS50 IDE is a cloud-based machine running Ubuntu, one of the many flavors of the Linux OS.
2. Many modern Linux distributions have graphical user interfaces (GUI) to allow easy mouse-based navigation.
3. Still, as a programmer you'll likely be using your terminal window frequently, and you can do many of the same tasks with keyboard commands.
4. Let's have a look at some of the most important of these keyboard-based commands for working within the IDE or any UNIX-based system.
   1. ls
      1. Short for "list", this command will give you a readout of all the files and current folder in your current directory.
   2. cd ‹directory >
      1. Short for "change directory", this command change your current directory to ‹ directory>, which you specify, in your workspace or on your operating system.
      2. The shorthand name for the current directory is .
      3. The shorthand name for the parent directory of the current directory is ..
      4. If ever curious about the name of the current directory, though the terminal prompt will often tell you, you can type pwd (present working directory).
   3. mkdir < directory>
      1. Short for "make directory", this command will create a new subdirectory called ‹ directory> located in the current directory.
   4. cp ‹ source > ‹destination›
      1.  Short for "copy", this command will allow you to create a duplicate of the file you specify as < source>, which it will save in ‹ destination›.
      2.  If you wish to copy entire directories, you'll need to modify the command slightly:
      3.  cp -r < source directory > ‹destination directory›
      4.  The "-p" stands for recursive, and tells cp to dive down into the directory and copy everything inside of it (including any subdirectories it might contain).
