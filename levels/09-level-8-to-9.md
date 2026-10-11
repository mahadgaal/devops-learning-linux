# Level 8 -> Level 9

## Goal
The password is the only line in `data.txt` that occurs once.

## Commands / approach

```bash
sort data.txt | uniq -u
```

## What I learned
uniq only compares neighbouring lines, so the data must be sorted first. The -u option prints lines that appear once.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
