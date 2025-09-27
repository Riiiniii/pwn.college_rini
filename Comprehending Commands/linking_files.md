# Challenge Name
Linking files

## My solve
**Flag:** `pwn.college{k6KhwD9G_pq-lY0xRcOWiMR9znb.QX5ETN1wyM3MzNzEzW}`

```bash
Connected!
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
ln: failed to create symbolic link '/home/hacker/not-the-flag': File exists
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
ln: failed to create symbolic link '/home/hacker/not-the-flag': File exists
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{k6KhwD9G_pq-lY0xRcOWiMR9znb.QX5ETN1wyM3MzNzEzW}
```

## What I learned
I learnt about the linking command "ln -s ... ..." where the first placeholder holds the file that is to be copied in the file in the second placeholder. 
I also learnt about the "file" command which is used to give us a description/type of file it is.

## References 
None.
