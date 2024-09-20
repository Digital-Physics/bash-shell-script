This .sh file is a basic bash script that demonstrates how to automate a process on a linux OS.

To overcome this error when running the script: "./my_test_script.sh: Permission denied" I ran the following code to give myself executable 
permission:

"chmod +x my_test_script.sh"

Then I reran the shell script:

"./my_test_script.sh"


This was done for practice using Linux commands. Some other commands used:

cat was used to read files

stat was used for details

echo was used to print content

touch was used to create files

nano was ued to edit files

mkdir to make directories

pwd to print working directory

ls to list the file contents of the current directory

ls -l to view permissions on a file for Owner, Group, Other

cd to change directories

| to pipe outputs to other commands

> to write content to a file

< to read content out of a file

ps -ef to see the processes running on the linux kernel

htop for interactive process analysis

grep "search-term" for searching for text

sed for modifying (e.g. echo "jeff" | sed "s/j/m/g"   => "meff" )

gzip for making files smaller

tar for archiving directories



other commands too: https://www.youtube.com/watch?v=LKCVKw9CzFo

