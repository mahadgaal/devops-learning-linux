# Level 6 -> Level 7

## Goal
The password is somewhere on the server in a file with the specified owner, group, and size.

## Commands / approach

```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat <file found by find>
```

## What I learned
I searched the whole system by owner, group and size, and 2>/dev/null hid the permission denied errors.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
