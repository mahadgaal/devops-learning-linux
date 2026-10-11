# Level 11 -> Level 12

## Goal
The password is encoded with ROT13 in `data.txt`.

## Commands / approach

```bash
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

## What I learned
This level used ROT13, which shifts letters by 13 places. tr can swap one character set for another to reverse it.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
