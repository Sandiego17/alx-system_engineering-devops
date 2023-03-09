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
	Scripte > chmod --reference=olleh hello
