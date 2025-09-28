# Challenge Name
Matching with ?
## My solve
**Flag:** `pwn.college{AV27UHvTDFmpwyY6DAc5OKO5IHu.QXyIDO0wyM3MzNzEzW}`

```bash
Connected!
This challenge resets your working directory to /home/hacker unless you change
directory properly...
This challenge resets your working directory to /home/hacker unless you change
directory properly...
hacker@globbing~matching-with-:~$ cd /?ha??enge
hacker@globbing~matching-with-:/challenge$ /challenge/run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{AV27UHvTDFmpwyY6DAc5OKO5IHu.QXyIDO0wyM3MzNzEzW}example triple ticks for bash
pwn.college{helloworld}
```

## What I learned
I learnt that when the terminal encounters "?" character in a argument, the shell treats it as a single-character wildcard. 
"?" is similar to "*" but ? acts as a wildcard for a single character while * acts as a wildcard for a set of characters.
## References 
None.
