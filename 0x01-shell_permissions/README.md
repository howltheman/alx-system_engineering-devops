su betty : switches current user to betty
id -un   : prints the effective username of the current user
id -gn   : prints all the groups the current user is part of.
sudo chown betty hello :  changes the owner of the file hello to the user betty
touch hello : creates empty file called 'hello'
chmod u+x ./hello : adds execute permission to the owner of the file hello.
chmod ug+x,o+r  hello : adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello :adds execution permission to the owner, the group owner and the other users, to the file hello
chmod ug-rwx 0+rwx : removes all permissions for file owner,group owner and gives all permission to others

