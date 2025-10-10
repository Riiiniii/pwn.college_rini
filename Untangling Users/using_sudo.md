  # Challenge Name
Using sudo

## My solve
**Flag:** `pwn.college{8g3NP022F3SN_KozXVGXX31XbK4.QX4UDN1wyM3MzNzEzW}`

```bash
Connected!
hacker@users~using-sudo:~$ sudo cat /flag
pwn.college{8g3NP022F3SN_KozXVGXX31XbK4.QX4UDN1wyM3MzNzEzW}
```

## What I learned
I learnt that "sudo" is a newer version of "su". The world has recently switched to using the sudo command. Unlike su, which relies on password authentication, sudo checks policies to determine whether the user is authorized to run commands as a root. 

## References 
None.
