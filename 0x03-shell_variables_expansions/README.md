0. alias ls="rm*" -this script  creates an alias using variable "ls" "rm*"
1. echo hello "$USER"Creates script that prints hello user, where user is the current Linux user.
2. export PATH=$PATH:/action - this script Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
3. echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) -Create a script that counts the number of directories in the PATH
4. 4-global_variables - Creats a script that lists environment variables
5. set - A script that lists all local variables and environment variables, and functions.
6. Best=school -This script creats a new Local variable.
7. export Best="school" -This script creats a new global variable
8. echo $(($TRUEKNOWLEDGE + 128)) - A script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE.
9. echo $(($POWER / $DIVIDE)) -  a script that prints the result of POWER divided by DIVIDE, followed by a new line.
10. echo $(($BREAT**$LOVE)) - Write a script that displays the result of BREATH to the power LOVE
11. 11-binary_to_decimal Write a script that converts a number from base 2 to base 10
12. echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" -Create a script that prints all possible combinations of two letters, except oo
13. printf "%.2f" $NUM | sort - Write's a script that prints a number with two decimal places, followed by a new line.
14. printf '%x\n' $DECIMAL - Write a script that converts a number from base 10 to base 16
15. tr `echo {a..z} | tr -d ' '` `echo {n..z} $(echo {a..m}) | tr -d ' '` | tr `echo {A..Z} | tr -d ' '` `echo {N..Z} $(echo {A..M}) | tr -d ' '` - Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
16. perl -lne 'print if $. % 2 == 1' -Write a script that prints every other line from the input, starting with the first line.
