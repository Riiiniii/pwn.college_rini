# Challenge Name
Extracting specific sections of text

## My solve
**Flag:** `pwn.college{ksNxM2RYm_s3sQ-bHgQZPtef-xE.01NxEzNxwyM3MzNzEzW}`

```bash
Connected!
hacker@data~extracting-specific-sections-of-text:~$ /challenge/run | cut -d " " -f 2 | tr -d "\n"
pwn.college{ksNxM2RYm_s3sQ-bHgQZPtef-xE.01NxEzNxwyM3MzNzEzW}
```

## What I learned
I learnt about the "cut" comamnd which is used to extract a specific column. | cut -d " " -f 2 |, here -d refers to delimited (how the columns are seperated), " " refers to the fact that the columns are seperated by a space and -f 2 refers to the second column.

## References 
None.
