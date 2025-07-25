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

The following types of issues are **not eligible** for bounty:

| Category                            | Example                                                                                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Non-security-impacting behavior     | Behaviors that cause inconvenience but do not pose a security risk (e.g. non-impactful file or resource creation, stack traces, version disclosure) |
| Outdated or unused components       | Reports of outdated libraries or open ports without a viable exploit                                                                                |
| Non-exploitable findings            | Theoretical vulnerabilities without realistic attack scenarios                                                                                      |
| Security headers and configurations | Missing or weak HTTP headers (e.g. CSP, X-Frame-Options)                                                                                            |
| Abuse without impact                | Reports like rate-limiting, brute force, or clickjacking without demonstrated impact                                                                |
| Self-inflicted vulnerabilities      | Issues requiring the user to attack themselves (e.g. Self-XSS)                                                                                      |
