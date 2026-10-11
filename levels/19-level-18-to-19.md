# Level 18 -> Level 19

## Goal
A modified shell configuration logs you out. Run a command directly over SSH to read `readme` without opening an interactive shell.

## Commands / approach

```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
```

## What I learned
The .bashrc logged me out on connect. Passing a command to ssh runs it without starting an interactive shell, so I could still read the file.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
