# Pecanception
Our pecan tree has had an amazing year with a large harvest.

However, it was so much that it has overflow our systems and pecans have encrypted our data.

Can you retrieve our data from the attached file? (the password will surely rock you)
# Solution
Now for this I used `stegseek` tool with `rockyou.txt` 
For installation : 
```bash
sudo apt install stegseek
```
Rockyou.txt : https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt

Now run the command 
```bash
stegseek filename wordlist.txt output.txt
``` 
or to print it in the console directly 
```bash
stegseek filename wordlist.txt
```
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/a7b48559-37dd-4ec7-8b09-1a7d04a5767d)
