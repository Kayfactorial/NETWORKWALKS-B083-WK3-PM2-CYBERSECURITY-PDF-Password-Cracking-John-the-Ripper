# NETWORKWALKS-B083-WK3-PM4-CYBERSECURITY-PDF-Password-Cracking-John-the-Ripper
Cracking a document password using JTR

# PDF Password Cracking with John the Ripper
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=2504B64&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flatsquare&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-JTR-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Skill-John%20the%20Ripper%20-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Adio%20Kabiru%20-C00000?style=flat-square" />
</p>
## Project Overview

This project documents my Week 3 Ethical Hacking assignment with NetworkWalks.

The objective was to recover the password of **My Locked PDF2** using **John the Ripper (JTR)** on Kali Linux.

The exercise was performed in a controlled cybersecurity lab environment.

## Tools Used

* Kali Linux
* John the Ripper (JTR)
* PDF hash extraction tools
* Terminal

## Project Methodology

The exercise followed these general steps:

1. Prepare the protected PDF for analysis.
2. Generate/extract the PDF hash.
3. Prepare the hash for John the Ripper.
4. Run John the Ripper against the extracted hash.
5. Recover the PDF password.
6. Enter the recovered password into the protected document.
7. Confirm successful access to the PDF.

## Screenshots

### 1. Cracking with Kali Linux

John the Ripper was used from the Kali Linux environment to perform the password recovery process.

![Cracking PDF with Kali Linux](screenshots/01-kali-cracking.png)

### 2. Generating the Hash and Recovering the Password

The PDF hash was generated and supplied to the cracking process.

![Generating hash and recovering password](screenshots/02-hash-and-password.png)

### 3. Entering the Recovered Password

The recovered password was entered into the protected PDF.

![Entering recovered password](screenshots/03-entering-password.png)

### 4. Accessing the Document

The password was accepted and the protected document was successfully opened.

![Accessing PDF](screenshots/04-document-access.png)

## Key Learning

This exercise provided practical experience with:

* PDF hash extraction
* John the Ripper
* Kali Linux
* Password recovery
* Hash-based password attacks
* Command-line cybersecurity tools

It also helped reinforce the importance of strong passwords and understanding how password-protected files can be subjected to offline password attacks.

## Ethical Considerations

John the Ripper should only be used against passwords, files or systems for which you have explicit authorization.

This project was completed strictly within the context of an authorized cybersecurity learning assignment.

## Learning Source

NetworkWalks Ethical Hacking Week 3 Assignment.

## Author

**Adio Gabriel**

Network Engineer | Network Security | Cybersecurity Learner
