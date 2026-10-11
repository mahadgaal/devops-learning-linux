# Level 12 → Level 13

## Goal
`data.txt` is a hexdump of a repeatedly compressed file. Reconstruct and identify/decompress it layer by layer.

## Commands / approach
```bash
mkdir -p /tmp/bandit12-work
cp data.txt /tmp/bandit12-work/
cd /tmp/bandit12-work
xxd -r data.txt > data.bin
file data.bin
```

## What I learned
`xxd -r` reverses a hexdump. Use `file` after each step to identify the format, then use the matching tool (`gzip -d`, `bzip2 -d`, or `xz -d`) and repeat until the content is readable. Work in `/tmp`, not the shared challenge directory.

## My notes / verification
- [ ] I completed this challenge myself.
- Commands I actually used (if different):
- Result verified:
- Questions / mistakes to revisit:

> Do not commit Bandit passwords, private keys, or other credentials. Record the commands and concepts, not the secret output.
