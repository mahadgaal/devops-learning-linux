# Level 20 -> Level 21

## Goal
Use `suconnect` with a local listener. The program checks the line received from the listener against the current password and returns the next password if it matches.

## Commands / approach

```bash
nc -l -p 1234
./suconnect 1234
```

## What I learned
I ran a netcat listener on a port I chose and sent the current password to it. Then I ran suconnect against that port, and it returned the next password when the line matched.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
