# Security Policy

## Supported Versions

Only the **latest version on the `main` branch** is actively maintained and receives security fixes. Older versions are not supported and may contain known vulnerabilities.

---

## Reporting a Vulnerability

**Please do not open a public GitHub issue for security vulnerabilities.**

Public disclosure before a fix is available puts all users at risk. Instead, report vulnerabilities privately using one of the following methods:

- **GitHub private vulnerability reporting** — use the [Security tab](../../security/advisories/new) on this repository if enabled
- **Direct message** — contact the maintainer via GitHub private message
- **Email** — use the contact address listed in the repository profile, if available

### What to include

Please provide as much detail as possible:

- A clear description of the vulnerability
- Steps to reproduce the issue
- The potential impact (data exposure, data loss, crash, privilege escalation, etc.)
- Any suggested mitigations or fixes, if you have them

The more detail you provide, the faster a fix can be developed and released.

---

## What to Expect

After receiving a report, the maintainer will:

1. **Acknowledge** the report promptly (typically within a few days)
2. **Investigate** and confirm the vulnerability
3. **Develop and release a fix** in a reasonable timeframe depending on severity
4. **Credit** the reporter in the release notes, unless you prefer to remain anonymous

---

## Responsible Disclosure

We ask that you:

- Give us a reasonable amount of time to address the issue before any public disclosure
- Avoid accessing, modifying, or deleting data that does not belong to you
- Not perform actions that could harm the availability of the service or other users

We appreciate responsible disclosure and are committed to working with security researchers in good faith.

---

## Scope

Common areas of concern include (but are not limited to):

- Exposure of user data or credentials
- Authentication or authorization bypass
- Code injection (XSS, command injection, etc.)
- Unintended data persistence or leakage
- Dependency vulnerabilities with a direct exploit path

Out of scope: issues in third-party dependencies that have no exploit path in this project, or theoretical vulnerabilities without a proof of concept.
