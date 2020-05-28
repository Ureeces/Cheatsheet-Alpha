# Cheatsheet-Alpha
Two Heads One Cheatsheet

Cd - change directory , is used to navigate to another folder from your PC. CD lets you go to a specific folder.

Pwd - print working directory , shows the current working directory. It prints the path of the working directory, starting from the root.

Mkdir - make directory , allows you to make a new directory. This command can create multiple directories at once.

Rm - remove (files) - rf , is used to remove objects such as files, directories, symbolic links and so on from the file system. You should be very careful while running rm command because once you delete the files then you are not able to recover the contents of files and directories.

Touch - create a file , is used to create new empty files. It is also used to change the timestamps ( dates and times ).

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

---

``mv [file] [destination]/`` - move or rename files

__Moving:__ ``mv file1 folder/`` - moves "file1" to directory "folder"

* The **"/" at the end of the destination is important** to identifying a directory - otherwise **YOU WILL RENAME THE FILE IF YOU DON'T PUT USE IT**
* You can move multiple files at a time

__Renaming:__ ``mv file1 file2`` - renames "file1" to "file2"
* You can rename both files AND directories this way

---

``man [command]`` - pulls up the user manual of the specified command

* Press 'q' to exit the page that ``man`` pulls up
* Use ``man`` to gain a deeper understanding of commands! 