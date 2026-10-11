# Level 16 → Level 17

## Goal
Find the relevant open port in the range `31000–32000`, then identify the service that returns the next password when given the current password.

## Commands / approach
```bash
nmap -p 31000-32000 localhost
```

## What I learned
Use the port scan results to identify candidate services. Test the ports indicated by the challenge using `nc` or `openssl s_client` with TLS as appropriate; enter the current password interactively. Record which port/protocol worked, but not the password.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
