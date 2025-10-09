# Challenge Name
Backgroounding processes

## My solve
**Flag:** `pwn.college{8FcAmpTvLXpKJ9KlYJ_QvK9YL4I.QX3QDO0wyM3MzNzEzW`

```bash
Connected!
hacker@processes~backgrounding-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running *and
not suspended* in this terminal... Let's check!

UID          PID STAT CMD
root         153 S+   bash /challenge/run
root         155 R+   ps -o user=UID,pid,stat,cmd

I don't see a second me!

To pass this level, you need to suspend me, resume the suspended process in the
background, and then launch a new version of me! You can background me with
Ctrl-Z (and resume me in the background with 'bg') or, if you're not ready to
do that for whatever reason, just hit Enter and I'll exit!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~backgrounding-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running *and
not suspended* in this terminal... Let's check!

UID          PID STAT CMD
root         153 T    bash /challenge/run
root         160 S+   bash /challenge/run
root         162 R+   ps -o user=UID,pid,stat,cmd

I found a second version of me, but it's suspended! Please resume it in the
background with the 'bg' command, then run me again.
hacker@processes~backgrounding-processes:~$ bg
[1]+ /challenge/run &
hacker@processes~backgrounding-processes:~$


Yay, I'm now running the background! Because of that, this text will probably
overlap weirdly with the shell prompt. Don't panic; just hit Enter a few times
to scroll this text out.

hacker@processes~backgrounding-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running *and
not suspended* in this terminal... Let's check!

UID          PID STAT CMD
root         153 S    bash /challenge/run
root         174 S    sleep 6h
root         175 S+   bash /challenge/run
root         177 R+   ps -o user=UID,pid,stat,cmd

Yay, I found another version of me running in the background! Here is the flag:
pwn.college{8FcAmpTvLXpKJ9KlYJ_QvK9YL4I.QX3QDO0wyM3MzNzEzW
```

## What I learned
I learnt that when we use the fg command, the already processing processes are stopped to resume the suspended processes. However, the "bg" command can be used to resume the suspended processes in the background without disturbing the ongoing processes in the terminal.
## References 
None.
