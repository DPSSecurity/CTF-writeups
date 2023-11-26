# Problem
The password for the next level is stored in a file called - located in the home directory

# Solution
Exit the SSH session for Level 0. We need to SSH into Level 1 using the password we obtained from Level 0.<br>
Run: `ssh bandit1@bandit.labs.overthewire.org -p 2220` to connect. When prompted to enter the password enter `NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL`.<br>

The file we're trying to print is simply titled with a dash (-). We need to include the full path to be able to view the file since it outputs nothing without the path. Run: `cat ./-`

# Next level's password
`rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi`
