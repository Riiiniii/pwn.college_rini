# Challenge Name
Named pipes

## My solve
**Flag:** `pwn.college{E4mIj9Lw7vUyfzBwwVXf8kYZkpt.01MzMDOxwyM3MzNzEzW}}`

```bash
Connected!
hacker@piping~named-pipes:~$ mkfifo /tmp/flag_fifo
hacker@piping~named-pipes:~$ ls
COLLEGE  PWN  a  flag  grep  instructions  myfile  myflag  not-the-flag  pwn  the-flag
hacker@piping~named-pipes:~$ /challenge/run > /tmp/flag_fifo
You're successfully redirecting /challenge/run to a FIFO at /tmp/flag_fifo!
Bash will now try to open the FIFO for writing, to pass it as the stdout of
/challenge/run. Recall that operations on FIFOs will *block* until both the
read side and the write side is open, so /challenge/run will not actually be
launched until you start reading from the FIFO!

Connected!
hacker@piping~named-pipes:~$ cat /tmp/flag_fifo
You've correctly redirected /challenge/run's stdout to a FIFO at
/tmp/flag_fifo! Here is your flag:
pwn.college{E4mIj9Lw7vUyfzBwwVXf8kYZkpt.01MzMDOxwyM3MzNzEzW}
```

## What I learned
I learnt what working with two terminals is like. I also learnt the "mkfifo" command which is used to create a FIFO.
## References 
None.
