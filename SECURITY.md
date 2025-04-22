# Security Policy

## Supported Versions

The `NEXT-3D` project is actively maintained, with security updates applied to the latest stable release. Older versions are not guaranteed to receive security patches.

| Version        | Supported          |
|----------------|--------------------|
| `main` (latest)| ✅                 |
| Previous tags  | ❌ (No guarantee)   |

Users are encouraged to utilize the latest version to ensure optimal security and performance.

## Reporting a Vulnerability

If you identify a security vulnerability within `NEXT-3D`, **please do not disclose it publicly**.

To report securely:

- **Email:** contact [at] next-3d [dot] com
- **Subject Line:** `Security Issue: NEXT-3D`
- Include:
  - A concise summary of the issue.
  - Steps to reproduce (if applicable).
  - Relevant logs, screenshots, or proof-of-concept code.
  - Assessment of severity, if known (e.g., low, medium, high, critical).

Acknowledgment of your report will be provided within **72 hours**, with a full response within **7 working days**, outlining the status and next steps, such as patch timelines or coordinated disclosure plans.

## Scope

This security policy pertains to:

- The core `NEXT-3D` repository.
- Simulation modules and visualization components.
- Official plugin architecture and associated interfaces.
- Data handling and storage mechanisms within the application.

Out of scope:

- Community/third-party plugins; issues should be reported to their respective maintainers.
- User implementation errors stemming from misuse of the repository.
- Hosting configurations outside the provided deployment guidelines.

## Security Practices

To maintain the integrity and security of `NEXT-3D`:

- Avoid running unverified code or plugins without thorough inspection.
- Ensure that sensitive research data is handled securely, with appropriate access controls and encryption where necessary.
- Deploy the application in secure and/or isolated environments, adhering to best practices for server and network security.
- When developing or integrating plugins, follow secure coding standards to prevent introducing vulnerabilities.

## Disclosure Policy

We adhere to a **coordinated disclosure** approach:

1. Validate the reported vulnerability.
2. Develop and test a patch to address the issue.
3. Notify affected stakeholders, if applicable.
4. Release the patch with clear documentation.
5. Publicly disclose the vulnerability details post-remediation, including any assigned CVE identifiers.

Contributors who responsibly disclose vulnerabilities will be acknowledged in the project's documentation, unless anonymity is requested.

---

*Note: This project does not currently offer a formal bug bounty program. However, researcher contributions to its security are highly valued and recognized.*
