0-iam_betty:	Create a script that switches the current user to the user betty.
1-whoami	Write a script that prints the effective username of the current user.
2-groups	Write a script that prints all the groups the current user is part of.
3-chwon betty hello	Write a script that changes the owner of the file hello to the user betty.
4-touch hello	Write a script that creates an empty file called hello.
5-chmod u+x hello	Write a script that adds execute permission to the owner of the file hello.
6-chmod ug+x,o+r hello	Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7-chmod ugo+x hello	Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
8-chmod 007 hello	Write a script that sets the permission to the file hello as follows:
9-chmod 753 hello	Write a script that sets the mode of the file hello to this:
10-chmod --reference=olleh hello	Write a script that sets the mode of the file hello the same as olleh’s mode.
11-chmod -R +111 */	Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12-mkdir -m 751 my_dir	Create a script that creates a directory called my_dir with permissions 751 in the working directory.
13-chgrp school hello	Write a script that changes the group owner to school for the file hello
