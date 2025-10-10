# Challenge Name
Executable shell scripts

## My solve
**Flag:** `pwn.college{84L1AIbEkta8F-J1vowvTVQvXoD.QX0cjM1wyM3MzNzEzW}`

```bash
Connected!
hacker@chaining~executable-shell-scripts:~$ echo -e "/challenge/solve" > x.sh
hacker@chaining~executable-shell-scripts:~$ ls -l
total 116
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
-rw-r--r-- 1 hacker hacker    17 Oct 10 19:26 x.sh
hacker@chaining~executable-shell-scripts:~$ chmod u=xr,g=xr,o=xr x.sh
hacker@chaining~executable-shell-scripts:~$ ./x.sh
Congratulations on your shell script execution! Your flag:
pwn.college{84L1AIbEkta8F-J1vowvTVQvXoD.QX0cjM1wyM3MzNzEzW}
```

## What I learned
I learnt that if my shell script is executable, i can directly run it without having to invoke bash.
## References 
None.
