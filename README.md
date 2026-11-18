# NETWORKWALKS# PDF Password Auditing Lab

## Overview

This repository documents practical learning in PDF password auditing using two different approaches:

1. **NetworkWalks tools on Windows** – Using the NetworkWalks Hash Calculator and Password Cracker to recover the password of a protected PDF.
2. **John the Ripper on Kali Linux** – Extracting PDF password hashes using `pdf2john` and attempting password recovery using John the Ripper.

The objective is to understand how password-protected PDF files can be assessed through authorised password auditing techniques.

## Tools and Technologies

### Windows
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker

### Kali Linux
- Kali Linux
- `pdf2john`
- John the Ripper (JTR)
- VirtualBox

## Lab Activities

### 1. NetworkWalks – Windows
- Extracted and processed the PDF password hash using the NetworkWalks tools.
- Used the Password Cracker to perform password recovery.
- Successfully recovered the password.

See: [NetworkWalks Windows Lab](./NetworkWalks-Windows/README.md)

### 2. John the Ripper – Kali Linux
- Located and used the `pdf2john` utility.
- Extracted the password hash from a protected PDF.
- Saved the extracted hash to a text file.
- Used John the Ripper with the PDF format to perform a dictionary attack.
- Successfully recovered the password from the R4 sample.

See: [John the Ripper Kali Lab](./John-the-Ripper-Kali/README.md)

### 3. Additional Practice
Explored PDF encryption with another synthetic PDF sample, including an R5/AES-256 encrypted document. The hash was extracted, and password recovery was tested. The outcome is not yet documented as successful.

## Key Learning Outcomes

- Understanding PDF password protection.
- Extracting password hashes from encrypted PDF documents.
- Understanding dictionary-based password attacks.
- Using Windows-based password auditing tools.
- Using Kali Linux and John the Ripper.
- Understanding the importance of strong passwords.

## Ethical Considerations

All activities documented here were performed on files used for authorised learning and practical cybersecurity exercises. Password auditing should only be conducted on files you own or have explicit permission to assess.

**Note:** Actual recovered passwords and complete password hashes are intentionally excluded from this public repository.-WK3-PM2-PASSWORD-CRACKING
