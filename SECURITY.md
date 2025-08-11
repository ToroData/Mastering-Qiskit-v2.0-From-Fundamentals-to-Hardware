# Security Policy

## Supported Versions

The current active development branch is:

| Version | Supported          |
| ------- | ------------------ |
| main    | ✅ Supported       |

Older branches are not maintained unless explicitly stated.

---

## Reporting a Vulnerability

If you discover a security vulnerability related to this project:

1. **Do not open a public GitHub issue**.
2. Send a detailed report to: **ricardraigada@outlook.es**.
3. Include:
   - A clear description of the vulnerability.
   - Steps to reproduce it.
   - Potential impact on users or the project.
   - Any suggestions for mitigation (if available).

---

## What to Report

Relevant security issues for this repository may include:

- **Code execution risks** in notebooks (e.g., unsafe system calls).
- **Malicious dependencies** or insecure versions of packages.
- **Leaking of sensitive data** (e.g., API keys, credentials).
- Vulnerabilities in GitHub Actions workflows that could allow:
  - Unauthorized code execution.
  - Exposure of repository secrets.

This repository is primarily educational material, so typical vulnerabilities will likely be related to:
- Code that could unintentionally harm the contributor’s environment.
- Unsafe instructions or commands that might compromise user systems.

---

## Response Process

- **Acknowledgement**: You will receive an acknowledgement within **72 hours**.
- **Investigation**: The maintainer will validate the vulnerability and assess its impact.
- **Fix Timeline**: Critical issues will be addressed as soon as possible; other issues will be scheduled based on severity and project priorities.
- **Disclosure**: Once fixed, a public advisory may be issued if the vulnerability is relevant for all users.

---

## Commitment

This project is open source and educational, but security is still important.  
All reports will be treated seriously, and credit will be given to security researchers who responsibly disclose vulnerabilities.

