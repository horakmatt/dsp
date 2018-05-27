# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  


Action | Command
-------|--------
show current working directory | `pwd`
create a directory | `mkdir`
delete a directory | `rm -r directory_name`
create a file with `touch` | `touch file_name`
delete a file | `rm filename`
rename a file | `mv file_name1 file_name_2`
list hidden files | `ls -a`
copy a file from one directory to another | `cp path1/file_name1 path2/file_name2`
change permissions to allow execution | `chmod 755 file_name`
concatenate and print files to stdout | `cat file1 file2 ...`
see the top n lines of a file | `head -n file_name`
preview contents of file | `more file_name` (hit space to advance page)

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

Command | Action
--------|-------
`ls`  | List file in the current directory
`ls -a`  | List files, including hidden files
`ls -l`  | List files with details including, permissions, date last modified, etc
`ls -lh`  | Same as `ls -l` but writes the size in easier-to-read format, eg. 19K instead of 19423
`ls -lah`  | Same as above, but lists hidden files, too
`ls -t`  | List files sorted by last modification
`ls -Glp`  | List files with details, color coded, and with directories followed by "/"

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

Command | Action
--------|-------
`ls -d` | Lists only directories
`ls -m` | For getting a comma-separated list of your files
`ls -r` | Reverse the sort order when listing (can combine with `ls -t`)
`ls -o` | Long list format but without group name
`ls -R` | Display subdirectories, too.
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

 

