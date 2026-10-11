# Level 5 → Level 6

## Goal
The password is in a file under `inhere` with the specified size, readable text content, and non-executable status.

## Commands / approach
```bash
find inhere -type f -size 1033c ! -executable
```

## What I learned
`find` filters files by type, exact size (`1033c` means 1,033 bytes), and executable status. Use `cat <path-found>` to read the matching file.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
