# who is it
## Problem
Someone just sent you an email claiming to be Google's co-founder Larry Page but you suspect a scam. Can you help us identify whose mail server the email actually originated from? Download the email file here. Flag: picoCTF{FirstnameLastname}
## Solution
1. the file is an email header, we can leverage mxtoolbox to format the content.
2. Based on the hint provided, we can find a suspicious ip `173.249.33.206` from Authentication field.
3. Query with `whois 173.249.33.206` we can find the owner's name: Wilhelm Zwalina

## flag
picoCTF{WilhelmZwalina}