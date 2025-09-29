# Challenge Name
Split-piping stderr and stdout

## My solve
**Flag:** `pwn.college{o6Fu5JqcpJwasnApy5a-eHjIypb.QXxQDM2wyM3MzNzEzW}`

```bash
Connected!
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > /challenge/planet 2> /challenge/the
bash: /challenge/planet: Permission denied
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > >(/challenge/planet) 2> >(/challenge/the)
Congratulations, you have learned a redirection technique that even experts
struggle with! Here is your flag:
pwn.college{o6Fu5JqcpJwasnApy5a-eHjIypb.QXxQDM2wyM3MzNzEzW}
```

## What I learned
I learnt using multiple commands at the same time in one line.

## References 
None.
