# Challenge Name
Suspending processes

## My solve
**Flag:** `pwn.college{klWMvyGoWcWvL-rQ66Q4_qzrGQI.QX1QDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         153     135  0 06:14 pts/0    00:00:00 bash /challenge/run
root         155     153  0 06:14 pts/0    00:00:00 ps -f

I don't see a second me!

To pass this level, you need to suspend me and launch me again! You can
background me with Ctrl-Z or, if you're not ready to do that for whatever
reason, just hit Enter and I'll exit!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         153     135  0 06:14 pts/0    00:00:00 bash /challenge/run
root         160     135  0 06:14 pts/0    00:00:00 bash /challenge/run
root         162     160  0 06:14 pts/0    00:00:00 ps -f

Yay, I found another version of me! Here is the flag:
pwn.college{klWMvyGoWcWvL-rQ66Q4_qzrGQI.QX1QDO0wyM3MzNzEzW}
```

## What I learned
I learnt that "control+z" is a less harsh version of control+c we learnt earlier. Control+z is used to suspend processes. 
## References 
None.
