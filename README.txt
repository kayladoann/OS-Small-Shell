CS374 - Operating System: Small Shell Project
Project 3 Repo for CS 374

Project Description:
For this project, I wrote "smallsh", a simple shell implemented in C that had to meet numerous requirements.
It had three built-in commands—exit, cd, and status—and gave access to other GNU/Linux commands by allowing the user to spawn and terminate foreground and background subprocesses. It also allowed the user to navigate a server's file structure, and it responded to signals such as SIGINT and SIGTSTP. It used the colon as its command prompt.

How to run it:
To complie, type 'gcc --std=gnu99 -o smallsh smallsh.c'

To test with the script that was given to us, type './p3testscript 2>&1'
