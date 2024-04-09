# bacrypt

Buddy API File Encryption and Decryption

# Overview

A python script to encrypt or decrypt Buddy API encrypted files.

Overwrites the file in place, so make a backup if you are unsure.

If password is unknown but mixed xor key is, raw option can be used.

# Usage

```
usage: bacrypt [-h] [-v] [-r] password file

positional arguments:
  password       password
  file           file

options:
  -h, --help     show this help message and exit
  -v, --version  show program's version number and exit
  -r, --raw      raw xor key as hex password
```

# Bugs

If you find a bug or have compatibility issues, please open a ticket under issues section for this repository.

# License

Copyright (c) 2024 JrMasterModelBuilder

Licensed under the Mozilla Public License, v. 2.0.

If this license does not work for you, feel free to contact me.
