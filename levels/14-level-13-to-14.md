# Level 13 → Level 14

## Goal
A private SSH key in the home directory can be used to log in as `bandit14`.

## Commands / approach
```bash
ls -l
ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
```

## What I learned
`ssh -i` selects a private key for authentication. Never copy the private key into this repository.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
