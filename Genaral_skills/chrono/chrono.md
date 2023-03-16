# chrono
## Problem
How to automate tasks to run at intervals on linux servers?

Additional details will be available after launching your challenge instance.

## Solution
After launching the instance, you'll get server, port, username and password
1. ssh to the server `ssh <username>@<server> -p <port>`
2. server will ask you the password, type `<password>` access the server
2. in the server, you can't find things with `$ls` command.
3. using `cd ..` twice looking around the parent directories, you can find a folder `challenge`
4. `cd challenge` to the folder, you can find a file called `metadata.json`
5. `cat metadata.json` , you'll found the flag.
## flag
picoCTF{Sch3DUL7NG_T45K3_L1NUX_7754e199}