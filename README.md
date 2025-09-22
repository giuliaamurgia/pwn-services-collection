# Pwn Services Collection

Collection of Dockerized vulnerable services for practicing binary exploitation.

## Important — about the writeups in `exploit.py`

Most services include a reference exploit named `exploit.py` which doubles as a writeup / working script. These scripts were developed against the containerized binaries provided in this repository. **Do not assume hardcoded addresses or offsets will work on your machine** — addresses can change between builds, libc versions, host OS etc.
