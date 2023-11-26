# Problem
The password for the next level is stored in a file called spaces in this filename located in the home directory

# Solution
Exit the SSH session for Level 2. We need to SSH into Level 3 using the password we obtained from Level 2.<br>
Run: `ssh bandit2@bandit.labs.overthewire.org -p 2220` to connect. When prompted to enter the password enter `rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi`.<br>

Run: `ls -alh` to list the files in the current directory.<br>
>-a = list hidden files<br>
>-l = long-list format<br>
>-h = human-readable format<br>

The `spaces in this filename` file is in the current directory. Type `cat spaces` then press tab to autofill the rest. Notices the spaces and how Linux deals with them. 

# Next level's password
`aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG`
