This Repo contains the following scripts that;

switches the current user to the user 'betty'
prints the effective username of the current user
prints all the groups the current user is part of
changes the owner of the file 'hello' to the user 'betty'
creates an empty file called 'hello'
execute permission to the owner of the file 'hello'
adds execute permission to the owner and the group owner, and read permission to other users, to the file 'hello'
adds execution permission to the owner, the group owner and the other users, to the file 'hello'
sets the permission to the file 'hello' as follows: Owner: no permission at all Group: no permission at all Other users: all the permissions
sets the mode of the file 'hello' to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
sets the mode of the file 'hello' the same as olleh’s mode. julien@ubuntu:/tmp/h$ ls -l total 8 -rwxrw-r-- 1 julien julien 42 Sep 20 14:45 10-mirror_permissions -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello -rw-rw-r-- 1 julien julien 0 Sep 20 14:43 olleh julien@ubuntu:/tmp/h$ ./10-mirror_permissions julien@ubuntu:/tmp/h$ ls -l total 8 -rwxrw-r-- 1 julien julien 42 Sep 20 14:45 10-mirror_permissions -rw-rw-r-- 1 julien julien 23 Sep 20 14:25 hello -rw-rw-r-- 1 julien julien 0 Sep 20 14:43 olleh julien@ubuntu:/tmp/h$
adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regula r files should not be changed.
creates a directory called my_dir with permissions 751 in the working directory
changes the group owner to school for the file hello
