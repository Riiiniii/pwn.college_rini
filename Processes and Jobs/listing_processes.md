# Challenge Name
Listing processes 

## My solve
**Flag:** `pwn.college{guo3cuBXI6j0jF7iqd7aVVD2kwP.QX4MDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@processes~listing-processes:~$ ps -efww
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 05:46 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/dojo-workspace/bin/dojo-init /run/dojo/bin/sleep 6h
root           7       1  0 05:46 ?        00:00:00 /run/dojo/bin/sleep 6h
root         132       1  0 05:46 ?        00:00:00 /challenge/32485-run-8355
root         135     132  0 05:46 ?        00:00:00 sleep 6h
hacker       137       0  0 05:46 pts/0    00:00:00 /nix/store/0nxvi9r5ymdlr2p24rjj9qzyms72zld1-bash-interactive-5.2p37/bin/bash /run/dojo/bin/ssh-entrypoint
hacker       143     137  0 05:46 pts/0    00:00:00 /run/dojo/bin/bash --login
hacker       152     143  0 05:46 pts/0    00:00:00 ps -efww
hacker@processes~listing-processes:~$ /challenge/32485-run-8355
Yahaha, you found me! Here is your flag:
pwn.college{guo3cuBXI6j0jF7iqd7aVVD2kwP.QX4MDO0wyM3MzNzEzW}
Now I will sleep for a while (so that you could find me with 'ps').
```

## What I learned
I learnt that the "ps" command is used to show the process status. For additional information about the processes, commands such as "ps -ef" and "ps aux" can be used.
## References 
None.
