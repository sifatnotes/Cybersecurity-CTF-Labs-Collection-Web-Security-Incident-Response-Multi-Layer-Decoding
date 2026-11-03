# Cybersecurity-CTF-Labs-Collection-Web-Security-Incident-Response-Multi-Layer-Decoding
A curated, searchable index of hands-on CTF labs covering admin portal bypasses, payroll breach forensics, SQL injection data exfiltration, Caesar ciphers, and recursive encoding decoding from Learn SecByte.
# Web Security, Incident Response & Multi-Layer Decoding CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on Web Application Security & Incident Investigation (The Forgotten Admin Portal, Midnight Payroll Breach, SQL Injection Essentials), Classical Cryptanalysis (Caesar's Lost Letter), and Advanced Multi-Layer & Recursive Decoding (Lost in Translation, Recursive Decoder, The Encoding Onion, Triple Wrapped Flag, Decode Me If You Can) hosted on Learn SecByte.

This collection is designed for application security engineers, incident response analysts, DFIR practitioners, penetration testers, and security researchers seeking practical experience in investigating web breaches, exploiting authentication flaws, and unwrapping deeply nested data encodings.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Web Security & Incident Response Investigations](#web-security--incident-response-investigations)
  - [Classical Cryptanalysis & Substitution Ciphers](#classical-cryptanalysis--substitution-ciphers)
  - [Advanced Multi-Layer & Recursive Data Decoding](#advanced-multi-layer--recursive-data-decoding)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Modern enterprise environments face threats ranging from critical web application vulnerabilities to complex multi-stage obfuscation schemes. Defenders must quickly investigate administrative portal bypasses, trace unauthorized exfiltration during financial data breaches, and extract sensitive database records via SQL injection. Simultaneously, reverse engineering attacker payloads often requires navigating recursive, multi-layered encodings—peeling back successive transformations to recover hidden command-and-control payloads or flag data.

This repository organizes hands-on web security, breach investigation, and advanced decoding labs from Learn SecByte into structured learning paths covering web vulnerability triage and recursive payload analysis.

---

## Lab Collection & Index

| Lab Title | Domain Focus | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **The Forgotten Admin Portal** | Web AppSec | Hidden Portals & Authentication Bypass | [Access Lab](https://learn.secbyte.org/ctf/the-forgotten-admin-portal) |
| **Midnight Payroll Breach** | Incident Response | Financial Systems Breach & Exfiltration IR | [Access Lab](https://learn.secbyte.org/ctf/midnight-payroll-breach) |
| **SQL Injection Essentials** | Web AppSec | Login Bypass to Full Data Exfiltration | [Access Lab](https://learn.secbyte.org/ctf/sql-injection-essentials-from-login-bypass-to-data-exfiltrat) |
| **Caesar's Lost Letter** | Cryptanalysis | Classical Shift Ciphers & Message Recovery | [Access Lab](https://learn.secbyte.org/ctf/caesars-lost-letter) |
| **Lost in Translation** | Data Decoding | Multi-Format Character Set & Schema Triage | [Access Lab](https://learn.secbyte.org/ctf/lost-in-translation) |
| **Recursive Decoder** | Advanced Decoding | Automated & Scripted Multi-Pass Unpacking | [Access Lab](https://learn.secbyte.org/ctf/recursive-decoder) |
| **The Encoding Onion** | Advanced Decoding | Multi-Layer Base Encodings & Wrapper Triage | [Access Lab](https://learn.secbyte.org/ctf/the-encoding-onion) |
| **The Encoding Onion 6** | Advanced Decoding | Deep-Layer Encoding Challenge (Variant 6) | [Access Lab](https://learn.secbyte.org/ctf/the-encoding-onion6) |
| **Triple Wrapped Flag** | Data Decoding | Multi-Stage Encrypted & Encoded Wrapper | [Access Lab](https://learn.secbyte.org/ctf/triple-wrapped-flag) |
| **Triple Wrapped Flag 1** | Data Decoding | Multi-Stage Flag Extraction (Variant 1) | [Access Lab](https://learn.secbyte.org/ctf/triple-wrapped-flag1) |
| **Decode Me If You Can** | Advanced Decoding | Progressive Multi-Format Decoding Challenge | [Access Lab](https://learn.secbyte.org/ctf/decode-me-if-you-can) |
| **Decode Me If You Can 2** | Advanced Decoding | Advanced Multi-Format Challenge (Variant 2) | [Access Lab](https://learn.secbyte.org/ctf/decode-me-if-you-can2) |

---

## Categories

### Web Security & Incident Response Investigations
Hands-on CTF labs detailing administrative endpoint discovery, authentication controls, SQL injection data extraction, and financial breach incident response:

* **The Forgotten Admin Portal:** Discovering unlinked administrative directories, bypassing broken access control gates, and escalating web session privileges.
  * Lab Link: https://learn.secbyte.org/ctf/the-forgotten-admin-portal
* **Midnight Payroll Breach:** Reconstructing an intrusion timeline on corporate payroll servers, analyzing exfiltration paths, and triaging compromised credentials.
  * Lab Link: https://learn.secbyte.org/ctf/midnight-payroll-breach
* **SQL Injection Essentials:** Exploiting SQL injection flaws from initial authentication bypass (`' OR 1=1--`) to `UNION`-based schema enumeration and data exfiltration.
  * Lab Link: https://learn.secbyte.org/ctf/sql-injection-essentials-from-login-bypass-to-data-exfiltrat

### Classical Cryptanalysis & Substitution Ciphers
Practical security labs focused on historical shift ciphers and frequency analysis:

* **Caesar's Lost Letter:** Cryptanalyzing historical shift ciphers, identifying shift key offsets, and recovering plaintext communications.
  * Lab Link: https://learn.secbyte.org/ctf/caesars-lost-letter

### Advanced Multi-Layer & Recursive Data Decoding
Security forensics labs covering nested encodings, recursive decoding automation, and multi-wrapped payload unpacking:

* **Lost in Translation:** Resolving encoding mismatches, character set transformations (UTF-8, ASCII, Hex, URL-encoding), and corrupted string data.
  * Lab Link: https://learn.secbyte.org/ctf/lost-in-translation
* **Recursive Decoder:** Scripting automated recursive decoders using Python or CyberChef to process arbitrarily nested data streams.
  * Lab Link: https://learn.secbyte.org/ctf/recursive-decoder
* **The Encoding Onion & The Encoding Onion 6:** Peeling back multi-layered encoding wrappers (Base64 -> Base32 -> Hex -> Binary -> ASCII) across standard and advanced variants.
  * Lab Links:
    * The Encoding Onion: https://learn.secbyte.org/ctf/the-encoding-onion
    * The Encoding Onion 6: https://learn.secbyte.org/ctf/the-encoding-onion6
* **Triple Wrapped Flag & Triple Wrapped Flag 1:** Unwrapping multi-stage flag payloads protected by combined symmetric encryption and multi-format encoding wrappers.
  * Lab Links:
    * Triple Wrapped Flag: https://learn.secbyte.org/ctf/triple-wrapped-flag
    * Triple Wrapped Flag 1: https://learn.secbyte.org/ctf/triple-wrapped-flag1
* **Decode Me If You Can & Decode Me If You Can 2:** Solving progressive decoding challenges that test speed, script writing, and pattern recognition across complex data representations.
  * Lab Links:
    * Decode Me If You Can: https://learn.secbyte.org/ctf/decode-me-if-you-can
    * Decode Me If You Can 2: https://learn.secbyte.org/ctf/decode-me-if-you-can2

---

## Learning Path

Follow this structured roadmap to master web incident triage and recursive payload decoding:

1. **Web Vulnerability Exploitation & Breach Response**
   - Locate hidden administrative surfaces in The Forgotten Admin Portal.
   - Master database extraction in SQL Injection Essentials and investigate financial breach logs in Midnight Payroll Breach.
2. **Classical Cryptanalysis**
   - Solve key offset puzzles in Caesar's Lost Letter.
3. **Multi-Format Data Decoding**
   - Resolve character encoding issues in Lost in Translation and unwrap multi-stage flags in Triple Wrapped Flag.
4. **Recursive Payload Unpacking & Scripting Automation**
   - Automate multi-pass decoding using Recursive Decoder.
   - Master complex multi-layered wrapper challenges in The Encoding Onion and Decode Me If You Can.

---

## How to Use the Labs

1. Select a practice scenario from the index table or category breakdown above.
2. Launch the target lab environment directly on Learn SecByte using the provided access link.
3. Complete hands-on tasks using analytical and application security tools (Burp Suite, SQLmap, CyberChef, Python decoding scripts, `base64`, `xxd`, and browser developer tools).
4. Review post-lab writeups, secure coding remediations, and defensive incident response guides to strengthen your organization's security posture.

---

## Disclaimer

This repository is strictly intended for educational research, authorized penetration testing, and digital forensics practice. All concepts, tools, and lab environments are provided to help cybersecurity practitioners build practical expertise and defend enterprise web infrastructure. Unsanctioned vulnerability exploitation, unauthorized access attempts, or malicious payload distribution are strictly illegal.
