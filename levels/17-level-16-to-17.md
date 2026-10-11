# Level 16 -> Level 17

## Goal
Find the relevant open port in the range `31000â€“32000`, then identify the service that returns the next password when given the current password.

## Commands / approach

```bash
nmap -sV -p 31000-32000 localhost
openssl s_client -connect localhost:<port> -quiet
chmod 600 sshkey17.private
ssh -i sshkey17.private bandit17@localhost -p 2220
```

## What I learned
I scanned the port range with nmap to find which ports spoke SSL, then tested them until one returned a private key. SSH rejects keys with loose permissions, so chmod 600 was needed.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
