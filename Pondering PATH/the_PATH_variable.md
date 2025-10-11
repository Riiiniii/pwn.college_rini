# Challenge Name
The PATH variable

## My solve
**Flag:** `pwn.college{gqUB7zGUJvPb1pCSuK6nkL8YtIr.QX2cDM1wyM3MzNzEzW}`

```bash
Connected!
hacker@path~the-path-variable:~$ PATH=""
hacker@path~the-path-variable:~$ /challenge/run
Trying to remove /flag...
/challenge/run: line 4: rm: No such file or directory
The flag is still there! I might as well give it to you!
pwn.college{gqUB7zGUJvPb1pCSuK6nkL8YtIr.QX2cDM1wyM3MzNzEzW}
```

## What I learned
I learnt that if you keep the variable in the PATH command blank, things do not go as planned. So here, on using 'PATH=""' command, the rm command didnt work as intended and the flag wasnt deleted. 

## References 
None.
