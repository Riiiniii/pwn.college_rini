# Challenge Name
Duplicating piped data with tee

## My solve
**Flag:** `pwn.college{0xckWF4-sVlEBVWZI7QLZUi-1p6.QXxITO0wyM3MzNzEzW}`

```bash
Connected!
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee a | /challenge/college
Processing...
WARNING: you are overwriting file a with tee's output...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat a
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "0xckWF4-"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret 0xckWF4- | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{0xckWF4-sVlEBVWZI7QLZUi-1p6.QXxITO0wyM3MzNzEzW}
```

## What I learned
I learnt the usage of the "tee" command. This is used to duplicate the data flowing through the pipes to any other random file which you provide.

## References 
None.
