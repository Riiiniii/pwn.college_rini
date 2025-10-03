# Challenge Name
Deleting characters

## My solve
**Flag:** `pwn.college{kw63aw7fpqYYlvx2ty7uF8Z6r7L.0FNxEzNxwyM3MzNzEzW}`

```bash
Connected!
hacker@data~deleting-characters:~$ /challenge/run | tr -d ^%
Your character-stuffed flag:
pwn.college{kw63aw7fpqYYlvx2ty7uF8Z6r7L.0FNxEzNxwyM3MzNzEzW}
```

## What I learned
I learnt how to delete characters from a string. To do so, we use "| tr -d x" to delete x from the output.

## References 
None.
