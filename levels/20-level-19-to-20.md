# Level 19 -> Level 20

## Goal
Use the setuid executable `bandit20-do` to run a command as the next user and read that user's password file.

## Commands / approach

```bash
ls -la
./bandit20-do cat /etc/bandit_pass/bandit20
```

## What I learned
bandit20-do is a setuid binary, so it runs commands with its owner permissions. That let me read a file only the next user could read.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
