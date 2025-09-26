# Challenge Name
Touching files

## My solve
**Flag:** `pwn.college{wnZihd8RaZKcRIXnfM34Q0Eg1fP.QXwMDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.4mK6TfTSUV
hacker@commands~touching-files:/tmp$ cd /challenge
hacker@commands~touching-files:/challenge$ cat /challenge/run
#!/opt/pwn.college/bash

if [ ! -f /tmp/pwn ]
then
        fold -s <<< "Uh oh! /tmp/pwn does not exist. Please use the 'touch' command to create it!"
        exit 1
fi

if [ ! -f /tmp/college ]
then
        fold -s <<< "Uh oh! /tmp/college does not exist. Please use the 'touch' command to create it!"
        exit 2
fi

echo "Success! Here is your flag:"
cat /flag
hacker@commands~touching-files:/challenge$ cat /flag
cat: /flag: Permission denied
hacker@commands~touching-files:/challenge$ /challenge/run
Success! Here is your flag:
pwn.college{wnZihd8RaZKcRIXnfM34Q0Eg1fP.QXwMDO0wyM3MzNzEzW}
```

## What I learned
I learnt about the 'touch' command used to create files.
## References 
None.
