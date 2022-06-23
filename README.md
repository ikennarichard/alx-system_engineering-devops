Shell basics repository
Below you will find descritpions  for script the commands, what they are meant to do and how to use the linux terminal to set access rights for files and directories.

Note- Please ignore the square brackets is not part of the command, there are meant to highlight the commands.

0 - Change current user to betty, for this we use the [su] followed by username, we can also use it to switch current user to the root user.

1 - We use the [whoami] command to display the username of the current user.

2 - This script we enable to see all the groups the current user is part of use the [groups] command.

3 - Here we used [chown] to change the user of the file hello to betty

4 - This script will create an empty file  called hello, to make this possible we use the linux system [touch] command, eg. touch filename

5 - The [chmod] command is used to change the mode of the file hello, here we are giving execute rights to the current user of the file.

6- This script will give read, write and execute access to the owner, read and execute access to the group owner and read only access to other users.

7- Grant execute permission to the owner, the group owner and other users of the file hello

8- We will grant access other users, while the superuser and group user will have no permissions.

9- This script will set the mode of the file here, we full rights to the user, read/execute right to group user and write/execute rights to other users 

10- use the [chmod] along with the --reference flag to reference the file hello as olleh

11- Grant execute permission to all subdirectories of current directory for all user (superuser, group user, other users)

12- Create and set permissions for  directory my_dir 

13- This script will change the group user to school, we use the [chgrp] command to achieve this.

100- Change user:groupname of all files and directories in the current directory

101- Change user:group user of the symbolic link file- _hello

102 - This script will change user of file hello to (betty) if the user of the file is  guillaume

103 - Play Star Wars 4 in the terminal

  
