# Level 14 -> Level 15

## Goal
Submit the current level's password to the service listening on localhost port `30000`.

## Commands / approach

```bash
nc localhost 30000
```

## What I learned
netcat opens a raw TCP connection. I sent the current password to port 30000 and the service replied with the next one.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
