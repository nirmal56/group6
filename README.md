# group6
project assigned to group6-linux.
SCRIPT : Create a shell script which creates a list of all broken symbolic links on the system and print it. 

APPROACH:
first using touch command we have generated unique file name.
then by use of (ln -s) symbolic links are generated.
(ln) will generate hard link.

then after that we can delete all files by for loop, to delete selected file separetly one by one file is removed.
Now, the which are deleted will created broken link except hard links.(find . -xtype l) will search all broken links andall file names are stored to broken_links.txt
