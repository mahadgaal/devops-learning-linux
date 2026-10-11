# Level 15 -> Level 16

## Goal
Submit the current password to the SSL/TLS service on localhost port `30001`.

## Commands / approach

```bash
openssl s_client -connect localhost:30001 -quiet
```

## What I learned
This service needed TLS, so I used openssl s_client, which works like netcat but encrypted. The -quiet option hides the handshake output.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
