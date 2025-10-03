# Challenge Name
Translating characters

## My solve
**Flag:** `pwn.college{gEDZmzPQqgDWnGAnc0T_DX7MI1N.01MxEzNxwyM3MzNzEzW}`

```bash
Connected!
hacker@data~translating-characters:~$ /challenge/run | tr abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz
yOUR CASE-SWAPPED FLAG:
pwn.college{gEDZmzPQqgDWnGAnc0T_DX7MI1N.01MxEzNxwyM3MzNzEzW}

OR

Connected!
hacker@data~translating-characters:~$ /challenge/run | tr 'a-zA-Z' 'A-Za-z'
yOUR CASE-SWAPPED FLAG:
pwn.college{gEDZmzPQqgDWnGAnc0T_DX7MI1N.01MxEzNxwyM3MzNzEzW}
```

## What I learned
I learnt the "tr" command. It basically translates the characters provided in the first argument to the characters provided in the second argument.
## References 
None.
