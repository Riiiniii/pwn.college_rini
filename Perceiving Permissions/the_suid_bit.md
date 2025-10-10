# Challenge Name
The suid bit

## My solve
**Flag:** `pwn.college{0l70K3sZG3nHMB98bvHg82q98-6.QXzEjN0wyM3MzNzEzW}`

```bash
Connected!
hacker@permissions~the-suid-bit:~$ chmod u+s /challenge/getroot
hacker@permissions~the-suid-bit:~$ /challenge/getroot
SUCCESS! You have set the suid bit on this program, and it is running as root!
Here is your shell...
root@permissions~the-suid-bit:~# cat /flag
pwn.college{0l70K3sZG3nHMB98bvHg82q98-6.QXzEjN0wyM3MzNzEzW}
```

## What I learned
I learnt that suid permissions can be given by using the command "chmod u+s".
## References 
None.
