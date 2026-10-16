# OS Command Injection

## Executive Summary
Overview of command injection attacks, occurring when an application passes unsanitized user input directly to a system shell execution context[cite: 1].

## Key Concepts
- **Vulnerability Mechanics:** Attacker appends shell operators (`&`, `;`, `|`, `&&`, `||`) to execute arbitrary operating system commands[cite: 1].
- **Lab Takeaways (DVWA):** Bypassing basic blacklists/filters and extracting sensitive files (e.g., `/etc/passwd` or system network configuration)[cite: 1].
- **Impact:** System compromise, lateral movement, or host takeover.
- **Remediation:** Avoid system execution calls (`system()`, `exec()`), use parameterized API functions, and implement strict input allowlists.

## Practical Takeaway
Never pass raw user input into operating system shell calls; if system calls are unavoidable, strictly validate input against an allowlist of expected characters.
