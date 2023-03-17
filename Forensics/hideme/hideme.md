# hideme
## Problem
Every file gets a flag. The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye [here](/Forensics/hideme/flag.png).
## Solution
1. When click the file, it shows a .png. Let's analysis what's inside.
2. `binwalk -e flag.png`  to check the binary and extract file if there's a hiden file.
![binwalk](/Forensics/hideme/Screenshot_2023-03-17_11-29-56.png)
3. We got a `_flag.png.extracted` directory, the flag is in the _flag.png.extracted/secret/flag.png, open the png.
## flag
picoCTF{Hiddinng_An_imag3_within_@n_ima9e_cda72af0}
