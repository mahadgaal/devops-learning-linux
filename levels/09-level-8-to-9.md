# Level 8 → Level 9

## Goal
The password is the only line in `data.txt` that occurs once.

## Commands / approach
```bash
sort data.txt | uniq -u
```

## What I learned
`sort` puts identical lines together; `uniq -u` prints lines that occur exactly once.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
