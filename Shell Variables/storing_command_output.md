# Challenge Name
Storing command output 

## My solve
**Flag:** `pwn.college{EqWTP4GP2lwkTlSdPntmRDRdGIq.QX1cDN1wyM3MzNzEzW}`

```bash
Connected!
hacker@variables~storing-command-output:~$ PWN=$(/challenge/run)
Congratulations! You have read the flag into the PWN variable. Now print it out
and submit it!
hacker@variables~storing-command-output:~$ echo $PWN
pwn.college{EqWTP4GP2lwkTlSdPntmRDRdGIq.QX1cDN1wyM3MzNzEzW}
```

## What I learned
I learnt about how to store value in a variable directly from an output. This format for the same is "a=$()". This is called command substitution. 

## References 
None.
