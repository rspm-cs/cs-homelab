# CIA Triad

## Summary

The CIA Triad is a foundational cybersecurity model based on three pillars:

1. **Confidentiality** — protects data from unauthorized access.
2. **Integrity** — protects data from unauthorized modification, deletion, or corruption.
3. **Availability** — keeps systems, services, and data accessible when needed.

## Commands Used

- `gpg -c file.txt` — encrypt a file
- `gpg -d file.txt.gpg` — decrypt a file
- `gpg -o output.txt -d file.txt.gpg` — decrypt and save output to a new file
- `sha256sum file.txt` — generate a SHA-256 hash/checksum
- `cp source destination` — copy a file or directory
- `rm file.txt` — remove a file; warning: always double check the targeted files before executing 

## Key Idea

- **Encryption** supports confidentiality.
- **Hashing/checksums** support integrity.
- **Backups/copies** support availability.
