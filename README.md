# Cheatsheet-Alpha
Two Heads One Cheatsheet

Cd - change directory , is used to navigate to another folder from your PC. CD lets you go to a specific folder.

Pwd - print working directory , shows the current working directory. It prints the path of the working directory, starting from the root.

``cp [file] [destination]`` - copies file to another destination

__Example:__ ``cp file1 folder2`` will copy "file1" to directory named folder2

Special characters:

* ``cp -f`` - copy automatically deletes and overwrites existing files 
* ``cp -n`` - copy does not override existing files, making it useful for "safety and caution", takes precedence over ``-f``

---

``ls [options] [path]`` - lists files and directories within a directory

__Example:__ ``ls`` - will list all non-hidden files and directories(without a "." in the beginning of the name) in the current directory
* By specifying a [path], you can also get the list of the destination directory:
  * ``ls folder2`` - will list all files (except hidden ones, just like the normal one) in the directory named folder2 

Special characters:

* ``ls -a`` - lists ALL files, including hidden files and directories
* ``ls -R`` - recursively lists files and directories of BOTH current AND child directories  
* ``ls -1`` - puts the list in a single column

**You can combine these characters, for example: ``ls -a1 folder2`` will list ALL files and directories in the directory folder2 in a single column