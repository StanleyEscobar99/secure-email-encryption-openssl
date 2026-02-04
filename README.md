# Secure Email Communications Using OpenSSL (RSA)

## Overview
This project documents Lab 1.1: Securing Email Communications. The lab demonstrates
how public-key cryptography is used to protect sensitive data sent via email by
ensuring that only the intended recipient can decrypt the message.

## Tools Used
- Windows PowerShell
- OpenSSL
- Thunderbird

## Lab Steps Completed

### Step 1 — Create RSA Key Pair (ZYWIN01)
- Generated a 4096-bit RSA private key for Pasha using OpenSSL.
- Created a corresponding RSA public key to share with others.
- LAB.Securing.email.communications.1
- LAB.Securing.email.communications.1.1

### Step 2 — Share Public Key via Email (ZYWIN01 → ZYWIN02)
- Sent Pasha’s RSA public key to Rina using Thunderbird.
- Saved the public key on ZYWIN02 for encryption use.
- LAB.Securing.email.communications.2
- LAB.Securing.email.communications.2.1
- LAB.Securing.email.communications.2.2

### Step 3 — Encrypt Sensitive File (ZYWIN02)
- Encrypted `creditCardInfo.txt` using Pasha’s public key.
- Saved the encrypted output as `creditCardInfoEncrypted.txt`.
- LAB.Securing.email.communications.3

### Step 4 — Email Encrypted File to Pasha
- Sent `creditCardInfoEncrypted.txt` to Pasha via email.
- Ensured the file was protected during transmission.
- LAB.Securing.email.communications.4
- LAB.Securing.email.communications.4.1

### Step 5 — Decrypt File Using Private Key (ZYWIN01)
- Decrypted the encrypted file using Pasha’s RSA private key.
- Verified the original data was successfully restored.
- LAB.Securing.email.communications.5

## Skills Demonstrated
- Public-key cryptography (RSA)
- Secure email communication
- Encryption and decryption workflows
- Key generation and management
- Windows command-line security operations
