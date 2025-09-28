# Challenge Name
Matching with []

## My solve
**Flag:** `pwn.college{Qd5Yfs9Q0aFyAgtQEBKrdxqWyoK.QXzIDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@globbing~matching-with-:~$ cd /challenge
hacker@globbing~matching-with-:/challenge$ cd files
hacker@globbing~matching-with-:/challenge/files$ echo Look: file_[bash]
Look: file_a file_b file_h file_s
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bash]
You got it! Here is your flag!
pwn.college{Qd5Yfs9Q0aFyAgtQEBKrdxqWyoK.QXzIDO0wyM3MzNzEzW}
```

## What I learned
I learnt the use of [xyz]. It is used as a limited form of ?. We can mention the specific characters we want to check in case of [] which is not possible in case of ? as it checks all the characters.
file_[abcd] only checks if there is file_a, file_b, file_c or file_d.
## References 
None.
