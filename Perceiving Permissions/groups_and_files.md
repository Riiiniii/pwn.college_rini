# Challenge Name
Groups and files

## My solve
**Flag:** `pwn.college{sejBjisczD0EaNQTU0Tn9tFA3uj.QXxcjM1wyM3MzNzEzW}`

```bash
Connected!
hacker@permissions~groups-and-files:~$ id
uid=1000(hacker) gid=1000(hacker) groups=1000(hacker)
hacker@permissions~groups-and-files:~$ ls
COLLEGE  PWN  a  flag  grep  instructions  myfile  myflag  not-the-flag  pwn  the-flag
hacker@permissions~groups-and-files:~$ chgrp hacker flag
chgrp: cannot dereference 'flag': No such file or directory
hacker@permissions~groups-and-files:~$ chgrp hacker not-the-flag
hacker@permissions~groups-and-files:~$ cat not-the-flag
pwn.college{sejBjisczD0EaNQTU0Tn9tFA3uj.QXxcjM1wyM3MzNzEzW}
```

## What I learned
I learnt about the "chgrp" command. A user can be a part of multiple groups. The "id" command is used to view what all groups the user is a part of. Then we can use the chgrp command to give authority to a user other than the root to perform actions on it.
## References 
None.
