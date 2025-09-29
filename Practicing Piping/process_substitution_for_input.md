# Challenge Name
Process substitution for input

## My solve
**Flag:** `pwn.college{EnXVA3e41OtgFSdKybtkNPIzJ0W.0lNwMDOxwyM3MzNzEzW}`

```bash
Connected!
hacker@piping~process-substitution-for-input:~$ diff <(/challenge/print_decoys) <(/challenge/print_decoys_and_flag)
4a5
> pwn.college{EnXVA3e41OtgFSdKybtkNPIzJ0W.0lNwMDOxwyM3MzNzEzW}
```

## What I learned
I learnt that using "<(command)", the output of this command is hooked to a temporary file. 
## References 
None.
