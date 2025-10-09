# Challenge Name
Starting backgrounded processes

## My solve
**Flag:** `pwn.college{AXk6V44sZLFkaLFy2bJTVYyUEFH.QX5QDO0wyM3MzNzEzW}`

```bash
Connected!
hacker@processes~starting-backgrounded-processes:~$ bash: /channge/run: No such file or directory
/challenge/run &
[2] 139
[1]   Exit 127                /channge/run
hacker@processes~starting-backgrounded-processes:~$


Yay, you started me in the background! Because of that, this text will probably
overlap weirdly with the shell prompt, but you're used to that by now...

Anyways! Here is your flag!
pwn.college{AXk6V44sZLFkaLFy2bJTVYyUEFH.QX5QDO0wyM3MzNzEzW}
```

## What I learned
I learnt that you need not suspend a process to background it, you can directly background it. 
## References 
None.
