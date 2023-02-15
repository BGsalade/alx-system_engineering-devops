0. alias ls="rm*" -this script  creates an alias using variable "ls" "rm*"
1. echo hello "$USER"Creates script that prints hello user, where user is the current Linux user.
3. export PATH=$PATH:/action - this script Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
4. echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) -Create a script that counts the number of directories in the PATH
5. 4-global_variables - Creats a script that lists environment variables
6. set - A script that lists all local variables and environment variables, and functions.
