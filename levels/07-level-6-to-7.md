# Level 6 → Level 7

## Goal
The password is somewhere on the server in a file with the specified owner, group, and size.

## Commands / approach
```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

## What I learned
`find /` searches from the filesystem root. `2>/dev/null` suppresses permission-denied messages. Read the matching path with `cat <path-found>`.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
