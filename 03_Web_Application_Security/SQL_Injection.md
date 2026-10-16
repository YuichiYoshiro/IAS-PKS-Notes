# SQL Injection (SQLi)

## Executive Summary
Detailed analysis of SQL Injection vulnerabilities where malicious SQL statements are inserted into entry fields for execution against underlying databases.

## Key Concepts
- **Vulnerability Mechanics:** Caused by concatenating unsanitized user inputs directly into dynamic SQL query strings.
- **Exploitation Types:**
  - *In-Band / Error-Based:* Viewing direct database output or error messages on screen.
  - *Blind / Time-Based:* Inferring data character-by-character based on application response times or true/false behavior.
- **DVWA Lab Testing:** Exploiting input boxes on Low and Medium security configurations.
- **Remediation:** Using Parameterized Queries (Prepared Statements) and Stored Procedures to strictly separate code from data.

## Practical Takeaway
Prepared statements ensure that user inputs are always treated as literal parameter values rather than executable code, permanently preventing SQL injection.
