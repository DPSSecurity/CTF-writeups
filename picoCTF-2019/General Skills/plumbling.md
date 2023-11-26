# Problem Description
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to jupiter.challenges.picoctf.org 14291.

# Solution
Run: `nc jupiter.challenges.picoctf.org 14291 > output.txt` to connect and save the output. Next, we need to view the text file using `cat output.txt`. Notice how much text comes out! Instead, let's run: `cat output.txt | grep "picoCTF"` to obain the flag.

# Flag
`picoCTF{digital_plumb3r_ea8bfec7}`
