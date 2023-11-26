# Problem Description
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with nc jupiter.challenges.picoctf.org 15130.

# Solution
Run: `nc jupiter.challenges.picoctf.org 25103` to connect. We will need to [CyberChef](https://gchq.github.io/CyberChef/) to solve this challenge. It's the fastest and easiest for this specific challenge.<br>
Once connected, it will first print some binary it wants you to convert into ASCII within 45 seconds. Paste the binary into the input section of CyberChef and click the magic wand that appears next to the output section convert to ASCII.<br>
Next, it will print octal it wants you to convert into ASCII within 45 seconds again. Clear the input and output in CyberChef and then perform the same steps to convert to ASCII again.<br>
Final, it will print hex it wants you to convert into ASCII within 45 seconds again. Perform the same steps preivously to convert to ASCII.<br>

# Flag
`picoCTF{learning_about_converting_values_02167de8}`
