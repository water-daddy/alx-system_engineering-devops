#Shell Basics Tasks

Task 0: pwd === print working directory

Task 1: ls === list directory contents

Task 2: cd === change directory

Task 3: ls -l === list directory contents in long form

Task 4: ls -la === list directory contents in long form, including hidden files

Task 5: ls -la Note: Are files inherently ordered?

Task 6: mkdir /tmp/my_first_directory Create a my_first_directory directory inside the tmp directory

Task 7: mv /tmp/school /tmp/my_first_directory/school Move file school, which is located inside the tmp directory, to the my_first_directory directory, which is also 
located inside the tmp directory. This Task required some dir traversing.

Task 8: rm /tmp/my_first_directory/school Remove file school located in tmp/my_first_directory directory.

Task 9: rmdir /tmp/my_first_directory Remove directory my_first_directory located in directory tmp.

Task 10: cd - Change directory to the previous directory you were in.

Task 11: ls -la . .. /boot List all files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of working directory, and /boot directory. The ls command allows multiple directories to be listed separated by spaces.

Task 12: file /tmp/iamafile Prints the type of file iamafile.

Task 13: ln -s /bin/ls ls Create a symbolic link named ls for /bin/ls

Task 14: cp -u *.html .. Copy all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.


Task 15: mv [[:upper:]]* /tmp/u Move all files that begin with a capital letter to /tmp/u

Task 16: rm *~ Deletes all files in the current directory that end with a ~

Task 17: mkdir -p welcome/to/my_first_directory Create directory welcome in current directory. Create directory to inside directory welcome. Create directory my_first_directory inside directory to. The -p option creates any intermediate directories in the path argument.

Task 18: ls -pam List all files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

