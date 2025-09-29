# Challenge Name
Multi-word variables

## My solve
**Flag:** `pwn.college{85TlZpVYBYHRCq5RQ7C4LfYqOY3.QXwYTN0wyM3MzNzEzW}`

```bash
Connected!
hacker@variables~multi-word-variables:~$ PWN="COLLEGE YEAH"
You've set the PWN variable properly! As promised, here is the flag:
pwn.college{85TlZpVYBYHRCq5RQ7C4LfYqOY3.QXwYTN0wyM3MzNzEzW}
```

## What I learned
I learnt that to give a variable a multi word value, we must enclose it in quotes. So, a=HI THERE is wrong while a="HI THERE" works okay. We must still remember to add no spaces before or after = as that would make the shell think it is a different command.

## References 
None.
