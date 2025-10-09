# Challenge Name
Resuming processes

## My solve
**Flag:** `pwn.college{wBHIzJc4Un9jvsS1PNI-N5s0lDq.QX2QDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@processes~resuming-processes:~$ /challenge/run
Let's practice resuming processes! Suspend me with Ctrl-Z, then resume me with
the 'fg' command! Or just press Enter to quit me!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~resuming-processes:~$ fg
/challenge/run
I'm back! Here's your flag:
pwn.college{wBHIzJc4Un9jvsS1PNI-N5s0lDq.QX2QDO0wyM3MzNzEzW}
Don't forget to press Enter to quit me!
```

## What I learned
I learnt that the "fg" command is used to resume the suspended(ctrl+z) processes. If you do not have intentions to resume the process later on, you can just terminate(ctrl+c) the process. 
## References 
None.
