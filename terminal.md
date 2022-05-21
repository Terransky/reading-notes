# The Command Line
I know the assignment said no one liners but this section is literally about how to open the terminal. Not exactly riveting stuff. You can type echo $SHELL
to see your current shell. You can use the up and down arrow keys to traverse your command history.

# Basic Navigation
pwd will Print Working Directory to show which directory you're currently in.
ls will print a list of items in the directory. It can also take an optional \[options] and \[location] argument for different information.
~ will take you back to home directory, . is current directory, and .. will go up to the parent directory
cd path will change directory, without arguments will change to home directory
tab will autocomplete the directory you're typing

# More About Files
Linux doesn't use file extensions like Windows
the command file\[path\] will print the type of file it is
Linux is case sensitive unlike Windows so files with different casings are all distinct
to access files with spaces on the command line, they must be wrapped in quotes or the space must be back slashed
a . full stop in front of a file or directory will hide it. It can be found again through the -a modifier

# Manual Pages
commands can be looked up internally with man\[command name\]
if you don't know the command, you can search for keywords through man -k <\search term\>

# File Manipulation
mkdir name to create a new directory or folder
rmdir to delete a directory. -r option to recursively delete non empty directories and everything in it.
rm to delete a file.
Deletion cannot be undone.
touch name to create a blank file. It can also modify the access and modification times
cp source destination to copy a file
mv source destination to move a file and rename it. Move it to the same directory to overwrite the original file

# Cheat Sheet
Bookmarked for later reference, no doubt will be useful
