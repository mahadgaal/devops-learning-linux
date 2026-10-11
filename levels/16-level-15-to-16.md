# Level 15 → Level 16

## Goal
Submit the current password to the SSL/TLS service on localhost port `30001`.

## Commands / approach
```bash
openssl s_client -connect localhost:30001 -quiet
```

## What I learned
`openssl s_client` creates a TLS client connection. Enter the current password when connected.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
