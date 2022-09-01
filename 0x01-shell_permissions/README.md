This Repo contains the following scripts that;
1. switches the current user to the user 'betty'
2. prints the effective username of the current user
3. prints all the groups the current user is part of
4. changes the owner of the file 'hello' to the user 'betty'
5. creates an empty file called 'hello'
6. execute permission to the owner of the file 'hello'
7. adds execute permission to the owner and the group owner, and read permission to other users, to the file 'hello'
8. adds execution permission to the owner, the group owner and the other users, to the file 'hello'
9. sets the permission to the file 'hello' as follows:
	Owner: no permission at all
	Group: no permission at all
	Other users: all the permissions
10. sets the mode of the file 'hello' to this:
	-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
11. sets the mode of the file 'hello' the same as olleh’s mode.
	julien@ubuntu:/tmp/h$ ls -l
	total 8
	-rwxrw-r-- 1 julien julien 42 Sep 20 14:45 10-mirror_permissions
	-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
	-rw-rw-r-- 1 julien julien  0 Sep 20 14:43 olleh
	julien@ubuntu:/tmp/h$ ./10-mirror_permissions 
	julien@ubuntu:/tmp/h$ ls -l
	total 8
	-rwxrw-r-- 1 julien julien 42 Sep 20 14:45 10-mirror_permissions
	-rw-rw-r-- 1 julien julien 23 Sep 20 14:25 hello
	-rw-rw-r-- 1 julien julien  0 Sep 20 14:43 olleh
	julien@ubuntu:/tmp/h$
12. adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regula	r files should not be changed.
13. creates a directory called my_dir with permissions 751 in the working directory
14. changes the group owner to school for the file hello
