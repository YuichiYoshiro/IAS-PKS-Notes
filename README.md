# IAS-PKS-Notes
# Information Assurance & Security (IAS) - Personal Knowledge System (PKS)

Welcome to my **Personal Knowledge System (PKS)** for CIT312/ITL312: Information Assurance and Security. This repository houses curated concepts, practical lab workflows, exploit mechanics, and remediation patterns focused on hands-on cybersecurity.

---

## 🗂️ Knowledge Base Navigation

### 01. Automation & Environment
* [Bash Scripting & Linux Fundamentals](01_Automation_and_Environment/Bash_Scripting_and_Linux.md) — Shell basics, log parsing (`grep`/`awk`), and automation scripts.
* [Virtualization Setup](01_Automation_and_Environment/Virtualization_Setup.md) — Hypervisors, host vs. guest networking modes (NAT/Host-Only), and VM setup.

### 02. Applied Cryptography
* [Encryption Fundamentals & Mailvelope](02_Applied_Cryptography/Encryption_and_Mailvelope.md) — Symmetric vs. Asymmetric encryption, PGP/GPG key management, and web mail encryption.

### 03. Web Application Security
* [OWASP Top Security Risks](03_Web_Application_Security/OWASP_Top_Risks.md) — Breakdown of core web application vulnerabilities.
* [SQL Injection (SQLi)](03_Web_Application_Security/SQL_Injection.md) — Exploit mechanics, DVWA lab tests, and parameterized query fixes.
* [OS Command Injection](03_Web_Application_Security/OS_Command_Injection.md) — Shell command chaining (`&`, `;`, `|`), input filters, and safe execution practices.

### 04. Security Operations
* [Cybersecurity Incident Analysis](04_Incident_Response/Incident_Analysis_and_Handling.md) — Incident handling lifecycle (NIST SP 800-61), root cause analysis, and post-mortem reporting[cite: 2].

---

## 🛠️ Key Hands-On Environments
- **DVWA (Damn Vulnerable Web Application):** Web vulnerability testing ground.
- **Mailvelope / OpenPGP:** Browser-based message encryption and signing[cite: 2].
- **Virtualization:** VirtualBox / VMware host-isolated environments.

---

## 📝 Core Key Takeaways
1. **Never Trust User Input:** Unsanitized user inputs lead directly to catastrophic failures like SQL Injection and OS Command Injection[cite: 1, 2].
2. **Defense in Depth:** Combine application-level security (prepared statements) with infrastructure isolation (virtualized network modes)[cite: 1, 2].
3. **Cryptography in Practice:** Security relies on key management and asymmetric cryptography for identity verification and confidentiality[cite: 2].
