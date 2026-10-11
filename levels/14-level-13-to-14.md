# Level 13 -> Level 14

## Goal
A private SSH key in the home directory can be used to log in as `bandit14`.

## Commands / approach

```bash
ssh -i sshkey.private bandit14@localhost -p 2220
cat /etc/bandit_pass/bandit14
```

## What I learned
I logged in as the next user with a private SSH key instead of a password. The -i option picks the key file, and connecting to localhost logs in to the same machine as another user.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
