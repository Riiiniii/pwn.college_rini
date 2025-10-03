# Challenge Name
Extracting the first lines with head

## My solve
**Flag:** `pwn.college{A5Cn11Zj1wrrq6WyKDSWup7Vu05.0lNxEzNxwyM3MzNzEzW}`

```bash
Connected!
hacker@data~extracting-the-first-lines-with-head:~$ /challenge/pwn | head -n 7 | /challenge/college
Congratulations, you piped the right codes!
pwn.college{A5Cn11Zj1wrrq6WyKDSWup7Vu05.0lNxEzNxwyM3MzNzEzW}
```

## What I learned
I learnt about the "head -n 4" command which basically prints out the first 4 lines of the output. By default, "head" prints out first 10 lines of the output. 

## References 
None.
