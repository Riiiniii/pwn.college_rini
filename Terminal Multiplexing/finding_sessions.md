# Challenge Name
Finding sessions

## My solve
**Flag:** `pwn.college{MPQH70EjHq0yVh56p923oPlP941.01N4IDOxwyM3MzNzEzW}`

```bash
Connected!
hacker@terminal-multiplexing~finding-sessions:~$ screen -ls
There are screens on:
        163.pts-2.terminal-multiplexing~detaching-and-attaching (Remote or dead)
        145.session_06c5a2415cbd0a66    (Detached)
        148.session_f1e7209593b21ded    (Detached)
        151.session_0b0c504b124dd7bd    (Detached)
4 Sockets in /home/hacker/.screen.
hacker@terminal-multiplexing~finding-sessions:~$ screen -r session_06c5a2415cbd0a66
[detached from 145.session_06c5a2415cbd0a66]
hacker@terminal-multiplexing~finding-sessions:~$ screen -r session_f1e7209593v21ded
There is no screen to be resumed matching session_f1e7209593v21ded.
hacker@terminal-multiplexing~finding-sessions:~$ screen -r session_f1e7209593b21ded
[detached from 148.session_f1e7209593b21ded]
```

## What I learned
I learnt that the command "screen -ls" is used to view all the screens. From this list, we can retach a screen and continue with what we want to do. 
## References 
None.
