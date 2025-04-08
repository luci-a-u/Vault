# Vault - Payloads Collection

A curated repository of payloads, wordlists, and useful files for penetration testing, bug bounty, CTFs, and security research. Collected and maintained with ❤️ by the community.

## 📁 Directory Structure

Each file in this repo serves a specific purpose in the security testing lifecycle.

### 🔐 Password & Authentication

- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/10k-most-common-password.txt" target="_blank">10k-most-common-password.txt</a> – Top 10,000 common passwords.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/4-digi-otp-combinations-modified-by-aman.txt" target="_blank">4-digi-otp-combinations-modified-by-aman.txt</a> – Customized 4-digit OTPs.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/4-digits-0000-9999.txt" target="_blank">4-digits-0000-9999.txt</a> – Complete 4-digit number range (0000-9999).
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/6_digit_mix.txt" target="_blank">6_digit_mix.txt</a> – 6-digit mixed pattern list.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/cirt-default-usernames.txt" target="_blank">cirt-default-usernames.txt</a> – Default usernames from various vendors.

### 🐞 Web Exploitation Payloads

- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/12500-XSS-payloads.txt" target="_blank">12500-XSS-payloads.txt</a> – XSS payloads for fuzzing and bypasses.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/HTML5sec-Injections-Jhaddix.txt" target="_blank">HTML5sec-Injections-Jhaddix.txt</a> – HTML5 attack vectors.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/LFI-Jhaddix-payloads.txt" target="_blank">LFI-Jhaddix-payloads.txt</a> – Local File Inclusion payloads.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/SSI-Injection-Jhaddix.txt" target="_blank">SSI-Injection-Jhaddix.txt</a> – Server-Side Includes (SSI) payloads.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/sql-payloads.txt" target="_blank">sql-payloads.txt</a> – SQL Injection payloads.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/command-injection.txt" target="_blank">command-injection.txt</a> – Payloads for command injection.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/open-redirect-payloads.txt" target="_blank">open-redirect-payloads.txt</a> – Open redirect test strings.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/graphql.txt" target="_blank">graphql.txt</a> – GraphQL fuzzing and introspection payloads.

### 🧭 Discovery & Enumeration

- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/combined_directories.txt" target="_blank">combined_directories.txt</a> – Common directory paths.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/raft-large-directories-lowercase.txt" target="_blank">raft-large-directories-lowercase.txt</a> – Raft large directory wordlist (lowercase).
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/raft-large-files.txt" target="_blank">raft-large-files.txt</a> – Raft large files wordlist.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/subdomains-top1million-110000.txt" target="_blank">subdomains-top1million-110000.txt</a> – Top subdomains list (110k entries).
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/subdomains-top1million-5000.txt" target="_blank">subdomains-top1million-5000.txt</a> – Top 5k subdomains list.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/endpoints-payloads.txt" target="_blank">endpoints-payloads.txt</a> – Common API and web endpoints.

### 📦 Misc

- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/master.txt" target="_blank">master.txt</a> – Possibly a master wordlist or combo list.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/hydra.restore" target="_blank">hydra.restore</a> – Saved session from Hydra (for resuming bruteforce).
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/senstivejs.txt" target="_blank">senstivejs.txt</a> – JavaScript files with potentially sensitive data.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/common-payloads.txt" target="_blank">common-payloads.txt</a> – General-purpose payloads for testing.
- <a href="https://github.com/luci-a-u/Vault/blob/main/Payloads/Subdomain-Takeover.html" target="_blank">Subdomain-Takeover.html</a> – PoC template for subdomain takeover.

---

## 📚 Usage

Use these payloads with tools like:

- <a href="https://github.com/ffuf/ffuf" target="_blank">ffuf</a>
- <a href="https://portswigger.net/burp" target="_blank">Burp Suite</a>
- <a href="https://sqlmap.org/" target="_blank">sqlmap</a>
- <a href="https://github.com/xmendez/wfuzz" target="_blank">wfuzz</a>
- <a href="https://github.com/maurosoria/dirsearch" target="_blank">dirsearch</a>

---

## ⚠️ Disclaimer

This repository is intended for **educational** and **authorized testing** only. Use responsibly.

---

## ✨ Credits

Includes payloads and lists inspired by:

- Jhaddix  
- SecLists  
- HTML5 Security Cheat Sheets  
- Community contributions (and Aman 😉)
