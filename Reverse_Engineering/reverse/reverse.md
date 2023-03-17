# reverse
## Problem
Try reversing this file? Can ya? I forgot the password to this [file](/Reverse_Engineering/reverse/ret). Please find it for me?
## Solution
1. It's a elf file, try strings to fetch flag `strings ret`
2. get the following message 
`Enter the password to unlock this file:  
You entered: %s  Password correct, please see flag: picoCTF{3lf_r3v3r5ing_succe55ful_2f0131a4}`
![image](/Reverse_Engineering/reverse/Screenshot_2023-03-17_15-29-30.png)
## flag
picoCTF{3lf_r3v3r5ing_succe55ful_2f0131a4}