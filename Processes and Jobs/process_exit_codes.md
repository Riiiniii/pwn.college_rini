# Challenge Name
Process exit codes

## My solve
**Flag:** `pwn.college{UH5-bVeJG-nusfXcnnQ7QP7zAoX.QX5YDO1wyM3MzNzEzW}`

```bash
hacker@processes~process-exit-codes:~$ /challenge/get-code
Exiting with an error code!
hacker@processes~process-exit-codes:~$ echo /challenge/get-code $?
/challenge/get-code 47
hacker@processes~process-exit-codes:~$ /challenge/submit-code 47
CORRECT! Here is your flag:
pwn.college{UH5-bVeJG-nusfXcnnQ7QP7zAoX.QX5YDO1wyM3MzNzEzW}
```

## What I learned
I learnt that the command "echo <filename> $?" gives us the exit code of the process. It is 0 if a command succeeds and 1 or any other random number if command fails.
## References 
None.
