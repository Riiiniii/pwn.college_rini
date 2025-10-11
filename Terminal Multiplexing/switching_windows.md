# Challenge Name
Switching windows

## My solve
**Flag:** `pwn.college{ko9YXDpFiQb8GOY3mDsmH4CWZlg.0FO4IDOxwyM3MzNzEzW}`

```bash
first - screen -r 
hacker@terminal-multiplexing~switching-windows:~$  cat <<MSG
> Excellent work! You found window 0!
> Here is your flag: pwn.college{ko9YXDpFiQb8GOY3mDsmH4CWZlg.0FO4IDOxwyM3MzNzEzW}
> MSG
Excellent work! You found window 0!
Here is your flag: pwn.college{ko9YXDpFiQb8GOY3mDsmH4CWZlg.0FO4IDOxwyM3MzNzEzW}
hacker@terminal-multiplexing~switching-windows:~$
```

## What I learned
I learnt that a screen inside a terminal can act as much more than just a screen. The following commands can be used to perform particular functions:
ctrl-A c --> creates a new window
ctrl-A n --> next window
ctrl-A p --> previous window
ctrl-A 0 to ctrl-A 9 --> jump directly to any window between 0 to 9
ctrl-A " --> brings us a selection menu of all windows

## References 
None.
