# Challenge Name
Chnaging file ownership

## My solve
**Flag:** `pwn.college{g6KL3FBjBh5zUQZ1ylI2pnCHarX.QXxEjN0wyM3MzNzEzW}`

```bash
Connected!
hacker@permissions~changing-file-ownership:~$ chown hacker /flag
hacker@permissions~changing-file-ownership:~$ cat /flag
pwn.college{g6KL3FBjBh5zUQZ1ylI2pnCHarX.QXxEjN0wyM3MzNzEzW}
```

## What I learned
I learnt about the "chown" command. This command is used to change ownership of a file. Its syntax is "chown <user> <filename>". This way, the user gets the same permissions as the root would have gotten for the particular file.
## References 
None.
