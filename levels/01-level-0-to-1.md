# Level 0 -> Level 1

## Goal
The password for the next level is in a file named `readme` in the home directory.

## Commands / approach

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
```

## What I learned
I connected over SSH on port 2220 and used cat to read the readme file.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
