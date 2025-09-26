# Challenge Name
Making directories

## My solve
**Flag:** `pwn.college{QIhEOSpKF51I0l1pOBzCFMEUqSe.QXxMDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@commands~making-directories:~$ cd /
hacker@commands~making-directories:/$ mkdir tmp
mkdir: cannot create directory ‘tmp’: File exists
hacker@commands~making-directories:/$ ls
bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@commands~making-directories:/$ cd tmp
hacker@commands~making-directories:/tmp$ ls
bin  hsperfdata_root  tmp.4mK6TfTSUV
hacker@commands~making-directories:/tmp$ mkdir pwn
hacker@commands~making-directories:/tmp$ cd pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{QIhEOSpKF51I0l1pOBzCFMEUqSe.QXxMDO0wyM3MzNzEzW}
```

## What I learned
I learnt the "mkdir" command which makes a new directory and also used "touch" and the "cd" command.
## References 
None.
