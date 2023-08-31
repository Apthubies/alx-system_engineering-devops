su switches the current directory to the user betty
id -un prints the effective username of the current directory
groups prints all the groups the current user is part of
chown changes the owner of the file hello to betty
touch creates an empty file called hello
chmod u+x hello give the owner of the file hello permission to execute
chmod u+x,g+x,o+r helllo give the owner,groups and other users permission to the file
chmod ugo+x hello gives the owner, groups, and other users permissions
chmod 007 hello gives the owner of the file no permission, groups no permission and permission to other users
chmod 753 gives changes the name of the file hello
chmod --refrence=olleh hello gives the file name mirror permission
chmod -R ugo+X adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
mkdir -m 751 my_dir creates a directory eith the permission
chgrp school hello changes the group owner hello file
chown vincent:staff * changes the owner to vincent awnd the group owner to staff
chown -h vincent:staff _hello changes the file owners and makes it a symbolic link
