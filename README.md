# 🗂️ Bug Hunting Wordlists

This repository is a curated collection of wordlists and payloads for various types of security testing, specifically tailored for bug bounty hunters and security researchers.

## 📁 Contents

Below is a list of wordlists and their respective categories:

### 🛠️ Injection Payloads

- **Command Injection**
  - [`command_injection.txt`](Wordlist/command_injection.txt)
  - [`command_injection mini.txt`](command_injection%20mini.txt)
  - [`OS-Command-Injection-Unix-Payloads.txt`](OS-Command-Injection-Unix-Payloads.txt)

- **SQL Injection**
  - [`SQL-Injection-Auth-Bypass-Payloads.txt`](SQL-Injection-Auth-Bypass-Payloads.txt)
  - [`SQL-Injection-Payloads.txt`](SQL-Injection-Payloads.txt)
  - [`sqli.txt`](sqli.txt)

- **PHP Code Injection**
  - [`PHP-Code-Injections-Payloads.txt`](PHP-Code-Injections-Payloads.txt)
  - [`PHP-Code-injection.txt`](PHP-Code-injection.txt)

### 🕸️ XSS Payloads

- **Cross-Site Scripting (XSS)**
  - [`Cross-Site-Scripting-XSS-Payloads.txt`](Cross-Site-Scripting-XSS-Payloads.txt)
  - [`xss 20k.txt`](xss%2020k.txt)
  - [`xss 8k.txt`](xss%208k.txt)
  - [`xss mini.txt`](xss%20mini.txt)
  - [`xss_polyglots.txt`](xss_polyglots.txt)
  - [`xss_polyglots mini.txt`](xss_polyglots%20mini.txt)
  - [`xss_portswigger.txt`](xss_portswigger.txt)
  - [`xss.txt`](xss.txt)

### 🌐 Server-Side Attacks

- **Server-Side Request Forgery (SSRF)**
  - [`Server-Side-Request-Forgery-Payloads.txt`](Server-Side-Request-Forgery-Payloads.txt)

- **Server-Side Template Injection (SSTI)**
  - [`ssti.txt`](ssti.txt)
  - [`ssti mini.txt`](ssti%20mini.txt)

### 🔍 File Inclusion

- **Local/Remote File Inclusion**
  - **Linux:**
    - [`file_inclusion_linux.txt`](file_inclusion_linux.txt)
    - [`file_inclusion_linux mini.txt`](file_inclusion_linux%20mini.txt)
  - **Windows:**
    - [`file_inclusion_windows.txt`](file_inclusion_windows.txt)
    - [`file_inclusion_windows mini.txt`](file_inclusion_windows%20mini.txt)

### 🖥️ Operating System Specific

- **Linux**
  - [`Linux-Sensitive-Files.txt`](Linux-Sensitive-Files.txt)

- **Windows**
  - [`Windows-Sensitive-Files.txt`](Windows-Sensitive-Files.txt)

### 📂 Other Payloads and Wordlists

- **Apache**
  - [`apache.txt`](apache.txt)

- **WAF Bypass**
  - [`wafbypass.txt`](wafbypass.txt)

- **Open Redirect**
  - [`openredirect.txt`](openredirect.txt)

- **SSI/ESI Injection**
  - [`ssi_esi.txt`](ssi_esi.txt)

- **CRLF Injection**
  - [`crlf.txt`](crlf.txt)
  - [`crlf mini.txt`](crlf%20mini.txt)

- **Redos**
  - [`redos.txt`](redos.txt)

- **Juicy Files**
  - [`juicy_files.txt`](juicy_files.txt)

- **Media Types**
  - [`Media-Type-(MIME).txt`](Media-Type-(MIME).txt)

- **Trusted Resolvers**
  - [`trusted_resolvers.txt`](trusted_resolvers.txt)

- **Dangling Markup**
  - [`dangling_markup.txt`](dangling_markup.txt)

- **File Extensions**
  - [`File-Extensions-Wordlist.txt`](File-Extensions-Wordlist.txt)

- **Fuzzing**
  - [`fuzz.txt`](fuzz.txt)

## 📝 Notes

- **Zone.Identifier Files:** These are metadata files created by the Windows operating system. They are automatically generated and can be safely ignored.

## 📜 Usage

These wordlists can be used with tools like **Burp Suite**, **OWASP ZAP**, **ffuf**, **dirb**, **sqlmap**, and many others to test various vulnerabilities.
