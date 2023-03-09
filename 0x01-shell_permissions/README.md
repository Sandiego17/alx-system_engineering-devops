#0 - Create a script that switches the current user to the user "betty"
	Script > su betty
#1 - Write a script that prints the effective username of the current user
	Script > id -un
#2 - Write a script that prints all the groups the current user is part of
	Script > id -gn
#3 - Write a script that changes the owner of the file "hello" to the user "betty"
	Script > chown betty hello
#4 - Write a script that creates an empty file called "hello"
	Script > touch hello
