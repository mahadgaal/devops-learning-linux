# Level 5 -> Level 6

## Goal
The password is in a file under `inhere` with the specified size, readable text content, and non-executable status.

## Commands / approach

```bash
cd inhere
find . -type f -size 1033c ! -executable
cat <file found by find>
```

## What I learned
find can filter by type, exact size in bytes and executable status, and the ! negates a test.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
