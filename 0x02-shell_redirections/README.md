echo Hello, World -A  script that prints “Hello, World”, followed by a new line to the standard output.
echo ' "(Ôo)'\' -this is a script that displays a confused smiley
cat /etc/passwd - Displays the content of file /etc/passwd
cat etc/passwd /etc/hosts -display the content of both /etc/passwd and /etc/hosts
tail /etc/passwd - displays the last 10 lines of /etc/passwd
head /etc/passwd - displays the first 10 lines of /etc/passwd
head -3 iacta |tail -1 -this script displays the third line of the file "iacta"
echo "Best School" > \\\*\\\\"'\"t School\"\\\\\'\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) -Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School
ls -la >ls_cwd_content - a script that writes into the file ls_cwd_content the result of the command ls -la
tail -n 1 iacta >> iacta -This script duplicates the last line of the file "iacta"
find . -type f -name "*.js" -delete - this script deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d -not -name '.' | wc -l -cript that counts the number of directories and sub-directories in the current directory
ls -t1 | head -n 10 this script displays the 10 newest files in the current directory
sort | uniq -u -takes a list of words as input and prints only the words tha appear exactly once
grep -i "root" /etc/passwd -This script displays the lines containing the pattern "root" from /etc/passwd.
grep -c -i "bin" etc/passwd - diplays the number of lines that contain the pattern "bin" in the file /etc/passwd.
grep -i "root' -A 3 /etc/passwd -dislpays the lines conataining the pattern "root" and 3 lines after them in the file /etc/passwd
grep -i -v "bin" /etc/passwd -this script displays the number of lines inside the file " /etc/passwd/ " that do not contain the pattern "bin"
grep -i "Display all lines of the file /etc/ssh/sshd_config starting with a letteir
