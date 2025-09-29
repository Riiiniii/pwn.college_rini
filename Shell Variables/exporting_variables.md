# Challenge Name
Exporting variables

## My solve
**Flag:** `pwn.college{4kWDKOomDmWOba5xTyX8W3fb03u.QXyYTN0wyM3MzNzEzW}`

```bash
Connected!
hacker@variables~exporting-variables:~$ export PWN=COLLEGE
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ COLLEGE=PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ /challenge/run
CORRECT!
You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great
job! Here is your flag:
pwn.college{4kWDKOomDmWOba5xTyX8W3fb03u.QXyYTN0wyM3MzNzEzW}
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
```

## What I learned
I learnt the use of "export" command. 
## References 
None.
