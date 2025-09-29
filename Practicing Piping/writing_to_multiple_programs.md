# Challenge Name
Writing to multiple programs

## My solve
**Flag:** `pwn.college{8h91BKp80xguKB79evosoOtIAwd.QXwgDN1wyM3MzNzEzW}`

```bash
Connected!
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | tee >(/challenge/the) >(/challenge/planet)
This secret data must directly and simultaneously make it to /challenge/the and
/challenge/planet. Don't try to copy-paste it; it changes too fast.
1825626332894514209
Congratulations, you have duplicated data into the input of two programs! Here
is your flag:
pwn.college{8h91BKp80xguKB79evosoOtIAwd.QXwgDN1wyM3MzNzEzW}
```

## What I learned
I learnt using "|" and ">()" together in a command.
## References 
None.
