# Challenge Name
Killing processes

## My solve
**Flag:** `pwn.college{gPoCCjOz8RX6JM4EizCSyJfFDhd.QXyQDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@processes~killing-processes:~$ ps
    PID TTY          TIME CMD
    139 pts/0    00:00:00 ssh-entrypoint
    145 pts/0    00:00:00 bash
    154 pts/0    00:00:00 ps
hacker@processes~killing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 05:49 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/dojo-workspace/bin/dojo-i
root           7       1  0 05:49 ?        00:00:00 /run/dojo/bin/sleep 6h
root         135       1  0 05:49 ?        00:00:00 su -c /challenge/.launcher hacker
hacker       136     135  0 05:49 ?        00:00:00 /challenge/dont_run
hacker       137     136  0 05:49 ?        00:00:00 sleep 6h
hacker       139       0  0 05:49 pts/0    00:00:00 /nix/store/0nxvi9r5ymdlr2p24rjj9qzyms72zld1-bash-interactive-5.2p37/
hacker       145     139  0 05:49 pts/0    00:00:00 /run/dojo/bin/bash --login
hacker       155     145  0 05:50 pts/0    00:00:00 ps -ef
hacker@processes~killing-processes:~$ 137 kill
bash: 137: command not found
hacker@processes~killing-processes:~$ kill 137
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{gPoCCjOz8RX6JM4EizCSyJfFDhd.QXyQDO0wyM3MzNzEzW}
```

## What I learned
I learnt how to "kill" processes. We use the command "kill <pid>" to stop the particular process from running. 
## References 
None.
