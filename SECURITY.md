# Security Policy

## Supported Versions

Manager.io uses a continuous release model. All updates, including security fixes, are applied to the main branch and released as part of the latest version.

We do not maintain older versions or separate release branches. To benefit from the latest features and security updates, users should always run the most recent release.

| Version        | Supported            |
| -------------- | -------------------- |
| Latest Release | :white\_check\_mark: |
| Older Releases | :x:                  |

## Reporting a Vulnerability

To report a potential security vulnerability in Manager.io:

* Email us at **[contact@manager.io](mailto:contact@manager.io)**
* Do **not** disclose security issues publicly until we have investigated and responded.
* We aim to acknowledge all reports within **3 business days**.
* If the issue is confirmed, we typically provide a fix or mitigation plan within **7–14 business days**.

## Bounty Program

We award bounties for valid security vulnerabilities based on severity, impact, and exploitability. All decisions are at our discretion and are final. Eligible issues include (but are not limited to):

* Unauthorized access to data
* Remote code execution
* Privilege escalation
* Bypass of critical security mechanisms

## Out of Scope

The following types of issues are **not eligible** for bounty and may be ignored or closed without response:

| Category                         | Example                                                              |
| -------------------------------- | -------------------------------------------------------------------- |
| Stack traces                     | Errors that expose stack traces without leading to a security impact |
| Outdated dependencies            | Reports of outdated libraries without a working exploit              |
| Theoretical/non-exploitable bugs | Issues that have no realistic attack vector                          |
| Missing or weak security headers | e.g. lack of CSP, X-Frame-Options, etc.                              |
| Rate limiting or brute force     | Reports not accompanied by a viable attack or abuse scenario         |
| Clickjacking                     | Unless demonstrated with practical impact                            |
| Self-XSS                         | Requires user to input and execute their own malicious code          |
| Open ports                       | Reports of open ports without an exploit or access risk              |
| Version disclosure               | e.g. software version in HTTP headers                                |
