# Challenge Name
Redirecting input

## My solve
**Flag:** `pwn.college{01orUr1YXhNj3cYZEa6vmHFFv-y.QXwcTN0wyM3MzNzEzW}`

```bash
Connected!
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{01orUr1YXhNj3cYZEa6vmHFFv-y.QXwcTN0wyM3MzNzEzW}
```

## What I learned
I learnt that the way ">" is used for redirecting output, "<" is used to redirect input.
## References 
None.
