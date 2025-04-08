# Vault - Payloads Collection

A curated repository of payloads, wordlists, and useful files for penetration testing, bug bounty, CTFs, and security research. Collected and maintained with ❤️ by the community.

## 📁 Directory Structure

Each file in this repo serves a specific purpose in the security testing lifecycle.

### 🔐 Password & Authentication

- `10k-most-common-password.txt` - Top 10,000 common passwords.
- `4-digi-otp-combinations-modified-by-aman.txt` - Customized 4-digit OTPs.
- `4-digits-0000-9999.txt` - Complete 4-digit number range (0000-9999).
- `6_digit_mix.txt` - 6-digit mixed pattern list.
- `cirt-default-usernames.txt` - Default usernames from various vendors.

### 🐞 Web Exploitation Payloads

- `12500-XSS-payloads.txt` - XSS payloads for fuzzing and bypasses.
- `HTML5sec-Injections-Jhaddix.txt` - HTML5 attack vectors.
- `LFI-Jhaddix-payloads.txt` - Local File Inclusion payloads.
- `SSI-Injection-Jhaddix.txt` - Server-Side Includes (SSI) payloads.
- `sql-payloads.txt` - SQL Injection payloads.
- `command-injection.txt` - Payloads for command injection.
- `open-redirect-payloads.txt` - Open redirect test strings.
- `graphql.txt` - GraphQL fuzzing and introspection payloads.

### 🧭 Discovery & Enumeration

- `combined_directories.txt` - Common directory paths.
- `raft-large-directories-lowercase.txt` - Raft large directory wordlist (lowercase).
- `raft-large-files.txt` - Raft large files wordlist.
- `subdomains-top1million-110000.txt` - Top subdomains list (110k entries).
- `subdomains-top1million-5000.txt` - Top 5k subdomains list.
- `endpoints-payloads.txt` - Common API and web endpoints.

### 📦 Misc

- `master.txt` - Possibly a master wordlist or combo list.
- `hydra.restore` - Saved session from Hydra (for resuming bruteforce).
- `senstivejs.txt` - JavaScript files with potentially sensitive data.
- `common-payloads.txt` - General-purpose payloads for testing.
- `Subdomain-Takeover.html` - PoC template for subdomain takeover.

---

## 📚 Usage

Use these payloads with tools like:

- [`ffuf`](https://github.com/ffuf/ffuf)
- [`Burp Suite`](https://portswigger.net/burp)
- [`sqlmap`](https://sqlmap.org/)
- [`wfuzz`](https://github.com/xmendez/wfuzz)
- [`dirsearch`](https://github.com/maurosoria/dirsearch)

## ⚠️ Disclaimer

This repository is intended for **educational** and **authorized testing** only. Use responsibly.

---

## ✨ Credits

Includes payloads and lists inspired by:

- Jhaddix
- SecLists
- HTML5 Security Cheat Sheets
- Community contributions (and Aman 😉)


