# Challenge Name
Listing files

## My solve
**Flag:** `pwn.college{EpgRB_M4Ba5UU3ixwlYubMhJXLF.QX4IDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@commands~listing-files:~$ cd /
hacker@commands~listing-files:/$ /challenge
bash: /challenge: Is a directory
hacker@commands~listing-files:/$ cd /challenge
hacker@commands~listing-files:/challenge$ ls
18287-renamed-run-32723  DESCRIPTION.md
hacker@commands~listing-files:/challenge$ cat /challenge/18287-renamed-run-32723
#!/opt/pwn.college/bash

echo "Yahaha, you found me! Here is your flag:"
cat /flag
hacker@commands~listing-files:/challenge$ /challenge/18287-renamed-run-32723
Yahaha, you found me! Here is your flag:
pwn.college{EpgRB_M4Ba5UU3ixwlYubMhJXLF.QX4IDO0wyM3MzNzEzW}
hacker@commands~listing-files:/challenge$
```

## What I learned
I learnt the 'ls' command here.
## References 
None.
