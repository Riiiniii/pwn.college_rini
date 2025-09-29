# Challenge Name
Grepping live output 

## My solve
**Flag:** `pwn.college{QpL4hSSrZngP9cwrl1_bsMsde8e.QX5EDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@piping~grepping-live-output:~$ /challenge/run | grep pwn.college
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge checks for a specific process at the other end of stdout : grep
[INFO] - the challenge will output a reward file if all the tests pass : /challenge/.data.txt

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /challenge/.data.txt file.

[TEST] You should have redirected my stdout to another process. Checking...
[TEST] Performing checks on that process!

[INFO] The process' executable is /nix/store/8b4vn1iyn6kqiisjvlmv67d1c0p3j6wj-gnugrep-3.11/bin/grep.
[INFO] This might be different than expected because of symbolic links (for example, from /usr/bin/python to /usr/bin/python3 to /usr/bin/python3.8).
[INFO] To pass the checks, the executable must be grep.

[PASS] You have passed the checks on the process on the other end of my stdout!
[PASS] Success! You have satisfied all execution requirements.
pwn.college{QpL4hSSrZngP9cwrl1_bsMsde8e.QX5EDO0wyM3MzNzEzW}
```

## What I learned
I learnt the "|" command. This command is used to directly connect the output of the left commnand to the input of the right. You need not store the value anywhere since this command directly just connects them.

## References 
None.
