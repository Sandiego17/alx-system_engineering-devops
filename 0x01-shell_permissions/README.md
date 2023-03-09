#0 - Create a script that switches the current user to the user "betty".
	Script > su betty
#1 - Write a script that prints the effective username of the current user.
	Script > id -un
#2 - Write a script that prints all the groups the current user is part of.
	Script > id -gn
#3 - Write a script that changes the owner of the file "hello" to the user "betty".
	Script > chown betty hello
#4 - Write a script that creates an empty file called "hello".
	Script > touch hello
#5 - Write a script that adds execute permission to the owner of the file "hello".
	Script > chmod 744 hello
#6 - Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello".
	Script > chmod 754 hello
#7 - Write a script that adds execution permission to the owner, the group owner and the other users, to the file "hello".
	Script > chmod ugo+x hello
#8 - Write a script that sets the permission to the file "hello" as follow: owner(no permissions at all), group(no permissions at all), and other users(all the permissions). The file "hello" will be in the working directory. Use of commas is not allowed for this script.
	Script > chmod 007 hello
#9 - Write a script that sets the mode of the file "hello" to this: -rwxr-x-wx 1 julien julien 23 Sep 2014;25 hello.
	Script > chmod 753 hello
#10 - Write a script that sets the mode of the file "hello" the same as "olleh's" mode.
	Script > chmod --reference=olleh hello
#11 - Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should be changed.
	Script > chmod -R +X .
#12 - Create a script that creates a directory called "my_dir" with permissions 751 in the working directory.
	Script > mkdir -m 751 my_dir
#13 - Write a script that changes the group owner to "school" for the file "hello".
	Script > chgrp school hello
#14 - Write a script that changes the owner to "vincent" and the group owner to staff for all the files and directories in the woking directory.
	Script > chown -R vincent:staff .
#15 - Write a script that changes the owner and the group owner of "_hello" to "vincenet" and "staff" respectively. The file "_hello" is in the working directory. The file "_hello" is a symbolic link.
	Script > chown -h vincent:staff _hello
#16 - Write a script that changes the owner of the file "hello" to "betty" only if is is owned by the user "guillaume". The file "hello" will be in the working directory.
        Script > chown --from=guillaume betty hello
#17 - Write a script that will play the StarWars IV episode in the terminal.
	Script > telnet towel.blinkenlights.nl
