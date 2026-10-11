# Level 12 -> Level 13

## Goal
`data.txt` is a hexdump of a repeatedly compressed file. Reconstruct and identify/decompress it layer by layer.

## Commands / approach

```bash
mktemp -d
cp ~/data.txt .
xxd -r data.txt > data.bin
file data.bin
gzip -d / bzip2 -d / tar xf (repeated, checking with file each time)
cat <final file>
```

## What I learned
The data was a hexdump compressed several times. I reversed it with xxd -r, then used file after each step to see whether the next layer was gzip, bzip2 or tar. I worked in a temp folder because the home directory is read-only.

## My notes / verification
- [x] I completed this challenge myself.
- Completed: 2026-10-11

> Do not commit Bandit passwords, private keys, or other credentials.
