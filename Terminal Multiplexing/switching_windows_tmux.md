# Challenge Name
Switching windows (tmux)

## My solve
**Flag:** `pwn.college{0RVrsGBDdVCEyTwtt8bodoIw5pJ.0FM5IDOxwyM3MzNzEzW}`

```bash
tmux
ctrl-B w
choose window 0 from there and get the flag.


}
hacker@terminal-multiplexing~switching-windows-tmux:~$  cat <<MSG
> Excellent work! You found window 0!
> Here is your flag: pwn.college{0RVrsGBDdVCEyTwtt8bodoIw5pJ.0FM5IDOxwyM3MzNzEzW}
> MSG
Excellent work! You found window 0!
Here is your flag: pwn.college{0RVrsGBDdVCEyTwtt8bodoIw5pJ.0FM5IDOxwyM3MzNzEzW}
hacker@terminal-multiplexing~switching-windows-tmux:~$        
```

## What I learned
I learnt more about tmux. It is similar to the screen command but a more modern version of it. We only need to remember that here we use ctrl-B unlike while using screen command where we use ctrl-A. 
I also learnt about the window picker command "ctrl-B w" which displays all the windows and we can choose whichever one we need.

## References 
None.
