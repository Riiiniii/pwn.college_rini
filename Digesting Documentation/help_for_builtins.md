# Challenge Name
Help for builtins

## My solve
**Flag:** `pwn.college{YiGI9W7RO9eKdCWyFi-qmqqr1UV.QX0ETO0wyM3MzNzEzW}`

```bash
Connected!
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "YiGI9W7R".
hacker@man~help-for-builtins:~$ /challenge/challenge --secret YiGI9W7R
bash: /challenge/challenge: No such file or directory
hacker@man~help-for-builtins:~$ --secret YiGI9W7R
bash: --secret: command not found
hacker@man~help-for-builtins:~$ challenge --secret YiGI9W7R
Correct! Here is your flag!
pwn.college{YiGI9W7RO9eKdCWyFi-qmqqr1UV.QX0ETO0wyM3MzNzEzW}
```

## What I learned
I learnt about the builtin "help" command. 

## References 
None.
