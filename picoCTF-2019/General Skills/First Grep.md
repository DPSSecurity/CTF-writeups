# Problem Description
Can you find the flag in file? This would be really tedious to look through manually, something tells me there is a better way.

# Solution
Download the file and run `strings <name of file> | grep "picoCTF"` to search through the file for the flag. Using `grep` allows us to search specfically for a text string of `picoCTF`.

# Flag
`picoCTF{grep_is_good_to_find_things_f77e0797}`
