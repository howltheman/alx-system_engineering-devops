su betty : switches current user to betty
id -un   : prints the effective username of the current user
id -gn   : prints all the groups the current user is part of.
sudo chown betty hello :  changes the owner of the file hello to the user betty
touch hello : creates empty file called 'hello'
chmod u+x ./hello : adds execute permission to the owner of the file hello.
chmod ug+x,o+r  hello : adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello :adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 : removes all permissions for file owner,group owner and gives all permission to others
chmod 753 :gives no permission to owner, read and write permission to group owner,read permission to others
chmod --reference = olleh hello :sets the mode of the file hello the same as olleh’s mode.
chmod -r ugo+x :adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
mkdir -m 751 my_dir: creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello :changes the group owner to school for the file hello
