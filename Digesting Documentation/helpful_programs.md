# Challenge Name
Helpful programs

## My solve
**Flag:** `pwn.college{U9PUuiIyoUkxSz8KZe04oRvOUyU.QX3IDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 980
hacker@man~helpful-programs:~$ /challenge/challenge -g 980
Correct usage! Your flag: pwn.college{U9PUuiIyoUkxSz8KZe04oRvOUyU.QX3IDO0wyM3MzNzEzW}
```

## What I learned
I learnt about how "--help" or "-h" as an argument tells us more about the command.

## References 
None.
