# Level 20 → Level 21

## Goal
Use `suconnect` with a local listener. The program checks the line received from the listener against the current password and returns the next password if it matches.

## Commands / approach
```bash
# Terminal 1: nc -l -p 12345
 # Terminal 2: ./suconnect 12345
```

## What I learned
Keep two SSH sessions open as `bandit20`. In one, start a netcat listener on a chosen port and send the current level password as a line; in the other, run `./suconnect <port>`. Netcat syntax can vary by implementation (for example, `nc -l 12345`). Never put the password in this file.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
