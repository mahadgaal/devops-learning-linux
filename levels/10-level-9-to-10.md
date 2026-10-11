# Level 9 -> Level 10

## Goal
The password is among human-readable strings in `data.txt`, preceded by several `=` characters.

## Commands / approach

```bash
strings data.txt | grep "=="
```

## What I learned
strings pulls readable text out of binary data, and grep narrowed it down to the lines with = characters.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
