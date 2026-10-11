# Level 9 → Level 10

## Goal
The password is among human-readable strings in `data.txt`, preceded by several `=` characters.

## Commands / approach
```bash
strings data.txt | grep '==='
```

## What I learned
`strings` extracts readable text from binary data; `grep` narrows the output to lines containing repeated equals signs.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
