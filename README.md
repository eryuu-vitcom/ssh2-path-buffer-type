## Description
### WARNING: This repository is a customized version of ssh2. You are probably looking for [this](https://github.com/mscdex/ssh2) ssh2 repository.

## CHANGES
This repository was customized specifically for a EUC-KR locale.

- Functions below were modified to accept EUC-KR encoded ```Buffer``` instead of ```string```
  - lib/protocol/SFTP.js :
    1. createReadStream
    1. createWriteStream
    1. stat
    1. mkdir
    1. rmdir
    1. rename
    1. unlink
