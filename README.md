# 🗂️ Bug Hunting Wordlists

This repository is a curated collection of wordlists and payloads for various types of security testing, specifically tailored for bug bounty hunters and security researchers.

## 📁 Contents

Below is a list of wordlists and their respective categories:

### 🛠️ Injection Payloads

- **Command Injection**
  - [`command_injection.txt`](Wordlists/command_injection.txt)
  - [`command_injection mini.txt`](Wordlists/command_injection%20mini.txt)
  - [`OS-Command-Injection-Unix-Payloads.txt`](Wordlists/OS-Command-Injection-Unix-Payloads.txt)

- **SQL Injection**
  - [`SQL-Injection-Auth-Bypass-Payloads.txt`](Wordlists/SQL-Injection-Auth-Bypass-Payloads.txt)
  - [`SQL-Injection-Payloads.txt`](Wordlists/SQL-Injection-Payloads.txt)
  - [`sqli.txt`](Wordlists/sqli.txt)
  - [`Login_Bypass.txt`](Wordlists/Login_bypass001.txt)

- **PHP Code Injection**
  - [`PHP-Code-Injections-Payloads.txt`](Wordlists/PHP-Code-Injections-Payloads.txt)
  - [`PHP-Code-injection.txt`](Wordlists/PHP-Code-injection.txt)

### 🕸️ XSS Payloads

- **Cross-Site Scripting (XSS)**
  - [`Cross-Site-Scripting-XSS-Payloads.txt`](Wordlists/Cross-Site-Scripting-XSS-Payloads.txt)
  - [`xss 20k.txt`](Wordlists/xss%2020k.txt)
  - [`xss 8k.txt`](Wordlists/xss%208k.txt)
  - [`xss mini.txt`](Wordlists/xss%20mini.txt)
  - [`xss_polyglots.txt`](Wordlists/xss_polyglots.txt)
  - [`xss_polyglots mini.txt`](Wordlists/xss_polyglots%20mini.txt)
  - [`xss_portswigger.txt`](Wordlists/xss_portswigger.txt)
  - [`xss.txt`](Wordlists/xss.txt)

### 🌐 Server-Side Attacks

- **Server-Side Request Forgery (SSRF)**
  - [`Server-Side-Request-Forgery-Payloads.txt`](Wordlists/Server-Side-Request-Forgery-Payloads.txt)

- **Server-Side Template Injection (SSTI)**
  - [`ssti.txt`](Wordlists/ssti.txt)
  - [`ssti mini.txt`](Wordlists/ssti%20mini.txt)

### 🔍 File Inclusion

- **Local/Remote File Inclusion**
  - **Linux:**
    - [`file_inclusion_linux.txt`](Wordlists/file_inclusion_linux.txt)
    - [`file_inclusion_linux mini.txt`](Wordlists/file_inclusion_linux%20mini.txt)
  - **Windows:**
    - [`file_inclusion_windows.txt`](Wordlists/file_inclusion_windows.txt)
    - [`file_inclusion_windows mini.txt`](Wordlists/file_inclusion_windows%20mini.txt)

### 🖥️ Operating System Specific

- **Linux**
  - [`Linux-Sensitive-Files.txt`](Wordlists/Linux-Sensitive-Files.txt)

- **Windows**
  - [`Windows-Sensitive-Files.txt`](Wordlists/Windows-Sensitive-Files.txt)

### 📂 Other Payloads and Wordlists

- **Apache**
  - [`apache.txt`](Wordlists/apache.txt)

- **WAF Bypass**
  - [`wafbypass.txt`](Wordlists/wafbypass.txt)

- **Open Redirect**
  - [`openredirect.txt`](Wordlists/openredirect.txt)

- **SSI/ESI Injection**
  - [`ssi_esi.txt`](Wordlists/ssi_esi.txt)

- **CRLF Injection**
  - [`crlf.txt`](Wordlists/crlf.txt)
  - [`crlf mini.txt`](Wordlists/crlf%20mini.txt)

- **Redos**
  - [`redos.txt`](Wordlists/redos.txt)

- **Juicy Files**
  - [`juicy_files.txt`](Wordlists/juicy_files.txt)

- **Media Types**
  - [`Media-Type-(MIME).txt`](Wordlists/Media-Type-(MIME).txt)

- **Trusted Resolvers**
  - [`trusted_resolvers.txt`](Wordlists/trusted_resolvers.txt)

- **Dangling Markup**
  - [`dangling_markup.txt`](Wordlists/dangling_markup.txt)

- **File Extensions**
  - [`File-Extensions-Wordlist.txt`](Wordlists/File-Extensions-Wordlist.txt)

- **Fuzzing**
  - [`fuzz.txt`](Wordlists/fuzz.txt)

## 📝 Notes

- **Zone.Identifier Files:** These are metadata files created by the Windows operating system. They are automatically generated and can be safely ignored.

## 📜 Usage

These wordlists can be used with tools like **Burp Suite**, **OWASP ZAP**, **ffuf**, **dirb**, **sqlmap**, and many others to test various vulnerabilities.
