# Challenge Name
Detaching and attaching

## My solve
**Flag:** `pwn.college{M22GFAXsfmcL1uAreek9FZxU8UX.0lN4IDOxwyM3MzNzEzW}`

```bash
Connected!
hacker@terminal-multiplexing~detaching-and-attaching:~$ screen
[detached from 139.pts-0.terminal-multiplexing~detaching-and-attaching]
hacker@terminal-multiplexing~detaching-and-attaching:~$ /challenge/run
Found detached screen session: 139.pts-0.terminal-multiplexing~detaching-and-attaching
Sending flag to your screen session...

Flag sent! Now reattach to your screen session with:

  screen -r

You'll find the flag waiting for you there!
hacker@terminal-multiplexing~detaching-and-attaching:~$ screen -r
Remove dead screens with 'screen -wipe'.
[screen is terminating]
```

## What I learned
I learnt that do detach a screen, we need to first do "ctrl+a" followed by "d" key. To retach a screen, we just use the "screen -r" command. 
## References 
None.
