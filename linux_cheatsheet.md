# Linux & Cryptography Fundamentals Cheat-Sheet

## Navigation & Files
- `pwd` : Print working directory
- `ls -la` : List all files with permissions
- `cd ..` : Go back one folder

## Permissions
- `chmod 777 file.txt` : Give absolute permissions to everyone
- `sudo chown root file.txt` : Change file owner to root

## Cryptography (OpenSSL)
- `sha256sum file.txt` : Generate a SHA256 file fingerprint
- `openssl enc -aes-256-cbc -salt -in file.txt -out encrypted.enc` : Encrypt a file
- `openssl enc -aes-256-cbc -d -in encrypted.enc -out decrypted.txt` : Decrypt a file
