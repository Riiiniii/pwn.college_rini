# Challenge Name
Changing permissions

## My solve
**Flag:** `pwn.college{IuI17whQg_O777UjUcs5CKP_eF5.QXzcjM1wyM3MzNzEzW}`

```bash
Connected!
hacker@permissions~changing-permissions:~$ ls -l
total 112
--w------- 1 hacker hacker     4 Sep 28 18:17 COLLEGE
--w------- 1 hacker hacker     8 Sep 29 14:05 PWN
--w------- 1 root   hacker    77 Sep 29 15:03 a
lrwxrwxrwx 1 hacker hacker    18 Sep 27 21:06 flag -> /challenge/catflag
--w------- 1 hacker hacker 73200 Sep 29 14:37 grep
--w------- 1 hacker hacker   829 Sep 28 20:07 instructions
--w------- 1 hacker hacker    15 Sep 28 18:36 myfile
--w------- 1 hacker hacker    95 Sep 28 20:07 myflag
lrwxrwxrwx 1 hacker hacker     5 Sep 27 21:11 not-the-flag -> /flag
--w------- 1 root   hacker    77 Sep 29 14:46 pwn
--w------- 1 hacker hacker   437 Sep 28 19:59 the-flag
hacker@permissions~changing-permissions:~$ chmod a+r not-the-flag
hacker@permissions~changing-permissions:~$ ls -l
total 112
--w------- 1 hacker hacker     4 Sep 28 18:17 COLLEGE
--w------- 1 hacker hacker     8 Sep 29 14:05 PWN
--w------- 1 root   hacker    77 Sep 29 15:03 a
lrwxrwxrwx 1 hacker hacker    18 Sep 27 21:06 flag -> /challenge/catflag
--w------- 1 hacker hacker 73200 Sep 29 14:37 grep
--w------- 1 hacker hacker   829 Sep 28 20:07 instructions
--w------- 1 hacker hacker    15 Sep 28 18:36 myfile
--w------- 1 hacker hacker    95 Sep 28 20:07 myflag
lrwxrwxrwx 1 hacker hacker     5 Sep 27 21:11 not-the-flag -> /flag
--w------- 1 root   hacker    77 Sep 29 14:46 pwn
--w------- 1 hacker hacker   437 Sep 28 19:59 the-flag
hacker@permissions~changing-permissions:~$ cat /flag
pwn.college{IuI17whQg_O777UjUcs5CKP_eF5.QXzcjM1wyM3MzNzEzW}
```

## What I learned
I learnt about how the "chmod" command is used to change the mode (read/write/execute) of a file at different levels (user/groups/all).
+ --> add permissions
- --> remove permissions
r --> read
w --> write
x --> execute
g --> group
o --> others
a --> all

## References 
None.
