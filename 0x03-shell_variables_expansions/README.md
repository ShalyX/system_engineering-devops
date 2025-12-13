The objective of this task is to ensure that you understand what aliases are and how to create them.

Create a script that creates an alias.

Name: ls
Value: rm *
Here is an example illustrating how you will use the script you create and how it will behave when you execute it.

julien@ubuntu:/tmp/0x03$ ls
0-alias  file1  file2
julien@ubuntu:/tmp/0x03$ source ./0-alias 
julien@ubuntu:/tmp/0x03$ ls
julien@ubuntu:/tmp/0x03$ \ls
julien@ubuntu:/tmp/0x03$ 
If you know how to create an alias, then all the task is asking of you is to write a simple bash script which when executed will create a new alias.

The example shown above illustrates how you will use the script that you create. Before adding your alias, the ls comand will list all files in the current directory. But as soon as the you create the alias for ls, executing it will remove all files in the directory.

NB: If any of the checks are failing, try the following:

Review the output of the checker and try to understand what is not working
Confirm that you have the right repository name on GitHub
Confirm that you have the right directory name (remember the naming is case sensitive)
Confirm that you have a README.md file in root of the repository and another one in the root of the directory and more importantly these files should not be empty.
