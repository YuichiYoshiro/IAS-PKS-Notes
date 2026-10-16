# OWASP Top Security Risks

## Executive Summary
A summary of the critical web application security risks defined by OWASP, focusing on vulnerability mechanisms, real-world impact, and general defensive posture[cite: 2].

## Key Concepts
- **A01: Broken Access Control:** Users acting outside of their intended permissions (e.g., IDOR, privilege escalation).
- **A02: Cryptographic Failures:** Data exposure due to weak algorithms, missing transport security, or hardcoded keys.
- **A03: Injection:** Untrusted data sent to an interpreter as part of a command or query (e.g., SQLi, Command Injection)[cite: 1, 2].
- **A04: Insecure Design:** Flaws inherent to business logic and system architecture rather than implementation bugs.

## Practical Takeaway
Adopting security-by-design and least-privilege principles addresses the majority of common web vulnerabilities before code reaches production environments.
