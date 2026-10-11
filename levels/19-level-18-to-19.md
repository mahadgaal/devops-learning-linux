# Level 18 → Level 19

## Goal
A modified shell configuration logs you out. Run a command directly over SSH to read `readme` without opening an interactive shell.

## Commands / approach
```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat readme"
```

## What I learned
SSH can execute a remote command directly. A non-interactive command avoids relying on an interactive login shell.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
