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

>> pwd = show current working directory path
>> mkdir = make new directory
>> rm -r = delete directory
>> touch = create new file
>> rm = delete a file
>> mv = can be used to rename a file
>> ls -a = shows hidden file
>> cp = copy a file from one directory to another
>> grep = search for a regex
>> uniq = remove adjacent duplicates
>> cat = output contents of a file
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

>> 'ls' lists the non-hidden files in current directory
>> 'ls-a' lists the hidden and non-hidden files in current directory
>> 'ls -l' lists non-hidden files in current directory in long form
>> 'ls -lh' lists non-hidden files in current directory in long form with file size
>> 'ls -lah' lists hidden and  non-hidden files in current directory in long form with file size
>> 'ls -t' lists non-hidden files in current directory by when last modified
>> 'ls -Glp' list non-hidden files in a long form, ungrouped and with directories seperated by slashes


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

>> -R = Display subdirectories as well
>> -c = Display files by file timestamp
>> -d = Display only directories
>> -t = Display newest files first
>> -u = Display files by file access time

 
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

>> xargs executes lists of arguments piece by piece, to a given command, so they can be processed by the command line without error.

>> $ xargs find -name
>> $ "*.txt"
