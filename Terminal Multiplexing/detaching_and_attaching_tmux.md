# Challenge Name
Detaching and attaching (tmux)

## My solve
**Flag:** `pwn.college{wp9DAcXjEtBdXMvIao7fD1MPHpD.0VO4IDOxwyM3MzNzEzW}`

```bash
Connected!
hacker@terminal-multiplexing~detaching-and-attaching-tmux:~$ tmux
[detached (from session 0)]
hacker@terminal-multiplexing~detaching-and-attaching-tmux:~$ /challenge/run
Found detached tmux session: 0
Sending flag to your tmux session...

Flag sent! Now reattach to your tmux session with:
  tmux attach

You'll find the flag waiting for you there!
hacker@terminal-multiplexing~detaching-and-attaching-tmux:~$ tmux attach
[exited]
```

## What I learned
I learnt that tmux is a younger, modern cousin of screen. To launch the screen, "tmux" command is used. Here, instead of ctrl-A, we use ctrl-B. To detach, ctrl-B followed by "d" is used. To retach, "tmux a" or "tmux attach" command can be used.

## References 
None.
