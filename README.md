# Encrypt/Decrypt script for Linux shell using Openssl
## Parameters
The script used the following parameters:
1. -m The mechanism you want to use: Either enc for encryption or dec for decryption
2. -s The string you want to encrypt or decrypt
3. -p The password for the encryption or decryption
## How to run the script
1. Make sure Openssl is installed: https://www.howtoforge.com/tutorial/how-to-install-openssl-from-source-on-linux/
2. Clone this repository
3. Make the script executable
```bash
sudo chmod -x encrypt_decrypt.sh
```
4. Encrypt 

```bash
./encrypt_decrypt.sh -m enc -s "This is a sample string" -p SuperS3curePassw0rd!
```
5. Decrypt

```bash
./encrypt_decrypt.sh -m dec -s "U2FsdGVkX1/mgl7Z+Y1cmNATJD/CnTHEFLlKhEwwUlpw8YYchYDoTAzMFGI20bIR" -p SuperS3curePassw0rd!
```
