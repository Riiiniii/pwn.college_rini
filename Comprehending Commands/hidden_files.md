# Challenge Name
Hidden files

## My solve
**Flag:** `pwn.college{INFXwNYYhvyGDOIczLVB8V-YiCy.QXwUDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls
bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv            bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-72671902227189  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ /.flag-72671902227189
bash: /.flag-72671902227189: Permission denied
hacker@commands~hidden-files:/$ cat /.flag-72671902227189
pwn.college{INFXwNYYhvyGDOIczLVB8V-YiCy.QXwUDO0wyM3MzNzEzW}
```

## What I learned
I learnt that 'ls' alone does not show the hidden files, so to view all the files, we use the command 'ls -a'.
## References 
None.
