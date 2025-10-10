# Challenge Name
Fun with group names

## My solve
**Flag:** `pwn.college{A8pdzabcuGZ0buycsjNkS9NIlkI.QXycjM1wyM3MzNzEzW}`

```bash
Connected!
hacker@permissions~fun-with-groups-names:~$ id
uid=1000(hacker) gid=1000(grp28399) groups=1000(grp28399)
hacker@permissions~fun-with-groups-names:~$ ls
COLLEGE  PWN  a  flag  grep  instructions  myfile  myflag  not-the-flag  pwn  the-flag
hacker@permissions~fun-with-groups-names:~$ chgrp grp28399 not-the-flag
hacker@permissions~fun-with-groups-names:~$ cat not-the-flag
pwn.college{A8pdzabcuGZ0buycsjNkS9NIlkI.QXycjM1wyM3MzNzEzW}
```

## What I learned
I learnt about the "chgrp" command.
## References 
None.
