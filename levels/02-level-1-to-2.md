# Level 1 → Level 2

## Goal
The password is in a file whose name is a single hyphen (`-`).

## Commands / approach
```bash
ls -la
cat ./-
```

## What I learned
`./-` makes the filename unambiguous. Without a path prefix, a leading hyphen can be interpreted as a command option.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
