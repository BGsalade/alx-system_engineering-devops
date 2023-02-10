su -changes the current user
whoami -prints the effective user id
groups -Prints the groups of which the user is a member
chown hello betty -Changes file ownership from (user)hello to (user)betty
touch - creates empty new file
chmod u+x [file] - adds adds executive permssion to the owner of the file
chmod ug+x,o+r -adds permission to owner and the group ownerwith read permission to other users
chmod ugo+x -adds execution permission to owner, the group and other users
chmod 007 -sets permission of file hello,owner :no permission,group:no permission,other:all permission
chmod 753 hello -sets mod of file  -rwxr-x-wx
chmod --reference=olleh hello  -sets mode of file hello same as olle's
chmod -R +X . -adds execute permission of all subdir of the current dir to the group owner and other users
