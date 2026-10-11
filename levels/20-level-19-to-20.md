# Level 19 → Level 20

## Goal
Use the setuid executable `bandit20-do` to run a command as the next user and read that user's password file.

## Commands / approach
```bash
ls -l bandit20-do
./bandit20-do id
./bandit20-do cat /etc/bandit_pass/bandit20
```

## What I learned
`./` runs a program from the current directory. A setuid program can run with its owner's effective user ID; use it only as intended by the challenge.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
