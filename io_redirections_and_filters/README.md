# Shell, I/O Redirections and filters

## I/O Redirection
In this lesson, we will explore a powerful feature used by command line
programs called input/output redirection. As we have seen, many commands such
as ls print their output on the display. This does not have to be the case,
   however. By using some special notations we can redirect the output of many
   commands to files, devices, and even to the input of other commands.

## Standard Output
Most command line programs that display their results do so by sending their
results to a facility called standard output. By default, standard output
directs its contents to the display.
## Standard Input
Many commands can accept input from a facility called standard input. By
default, standard input gets its contents from the keyboard, but like standard
output, it can be redirected.

### Task 0 - Hello World
Write a script that prints “Hello, World”, followed by a new line to the standard output.
### Task 1 - Confused smiley
Write a script that displays a confused smiley "(Ôo)'.
### Task 2 - Let's display a file
Display the content of the /etc/passwd file.
### Task 3 - What about 2?
Display the content of /etc/passwd and /etc/hosts
### Task 4 - Last lines of a file
Display the last 10 lines of /etc/passwd
### Task 5 -  I'd prefer the first ones actually
Display the first 10 lines of /etc/passwd
### Task 6 - Line #2
Write a script that displays the third line of the file iacta.

The file iacta will be in the working directory

* You’re not allowed to use sed
### Task 7 - It is a good file that cuts iron without making a noise
Write a shell script that creates a file named exactly
\*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending
by a new line.
### Task 8 - Save current state of directory
Write a script that writes into the file ls_cwd_content the result of the
command ls -la. If the file ls_cwd_content already exists, it should be
overwritten. If the file ls_cwd_content does not exist, create it.
### Task 9 - Duplicate last line
Write a script that duplicates the last line of the file iacta

*The file iacta will be in the working directory
### Task 10 - No more javascript
Write a script that deletes all the regular files (not the directories) with
a .js extension that are present in the current directory and all its subfolders.
### Task 11 - Don't just count your directories, make your directories count
Write a script that counts the number of directories and sub-directories in the current directory.

* The current and parent directories should not be taken into account
* Hidden directories should be counted
### Task 12 - What’s new
Create a script that displays the 10 newest files in the current directory.

Requirements:

* One file per line
* Sorted from the newest to the oldest
### Task 13 - Being unique is better than being perfect
Create a script that takes a list of words as input and prints only words that appear exactly once.

* Input format: One line, one word
* Output format: One line, one word
* Words should be sorted
### Task 14 -  It must be in that file
Display lines containing the pattern “root” from the file /etc/passwd
### Task 15 - Count that word
Display the number of lines that contain the pattern “bin” in the file /etc/passwd
### Task 16 - What's next?
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
### Task 17 -  I hate bins
Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
### Task 18 - Letters only please
Display all lines of the file /etc/ssh/sshd_config starting with a letter.

* include capital letters as well
### Task 19 -  A to Z
Replace all characters A and c from input to Z and e respectively.
### Task 20 - Without C, you would live in hiago
Create a script that removes all letters c and C from input.
### Task 21 - esreveR
Write a script that reverse its input.
### Task 22 - DJ Cut Killer
Write a script that displays all users and their home directories, sorted by users.

* Based on the the /etc/passwd file

