# Challenge Name
Redirecting script output

## My solve
**Flag:** `pwn.college{4oU337JGoxbcJihfyHtpNjVmlHS.QX4ETO0wyM3MzNzEzW}`

```bash
Connected!
hacker@chaining~redirecting-script-output:~$ echo -e "/challenge/pwn ; /challenge/college" > x.sh
hacker@chaining~redirecting-script-output:~$ bash x.sh | /challenge/solve
Correct! Here is your flag:
pwn.college{4oU337JGoxbcJihfyHtpNjVmlHS.QX4ETO0wyM3MzNzEzW}
```

## What I learned
I learnt that we can redirect output of the shell script as well because to the terminal it is only a command.
## References 
None.
