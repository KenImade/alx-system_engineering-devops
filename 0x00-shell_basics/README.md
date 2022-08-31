# Shell Basics
This Folder contains various shell basic commands/

pwd - script command to get the absolute path name of the current working directory/
ls - displays the content list of current directory/
cd - changes the working directory to the user's home directory/
ls -l - display current directory contents in a long format/
ls -la - display current directory contents, including hidden files/
ls -lna - display current directory contents in long format with user and group IDs displayed numerically and hidden files/
mkdir /tmp/my_first_directory - creates new directory in directory tmp/
mv file1 dir1 - moves file from directory to subdirectory dir1/
rm - removes file/
rm -r dir - deletes directory/
cd - -changes working directory to the previous one/
ls -al . .. /boot - lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
/
file /tmp/iamafile - prints the type of file named iamafile/
ln -a /bin/ls ls - creates a symbolic link to /bin/ls, named __ls__/
cp -rua *.html ../ - copies all the html files from the current working directory to the parent of the working directory but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent  of the working director/  
