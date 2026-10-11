# Level 17 → Level 18

## Goal
Compare `passwords.old` and `passwords.new`; the password is the changed line.

## Commands / approach
```bash
diff -u passwords.old passwords.new
```

## What I learned
`diff` displays differences between files. Identify the changed line and keep the password out of the repository.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
