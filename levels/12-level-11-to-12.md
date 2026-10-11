# Level 11 → Level 12

## Goal
The password is encoded with ROT13 in `data.txt`.

## Commands / approach
```bash
tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt
```

## What I learned
`tr` translates characters; these ranges rotate alphabetic characters by 13 positions.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
