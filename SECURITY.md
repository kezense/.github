# Security Policy

At **Kezense**, the security of our infrastructure and our clients' ML models is our top priority. We implement MLSecOps best practices to protect proprietary models, data, and deployments.

## Supported Versions

We provide security updates for the latest versions of our core automation engines and infrastructure modules. 

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take all security reports seriously. If you have discovered a potential security vulnerability in any Kezense repository, please do **not** disclose it publicly.

Instead, please report it to us privately:
1. Email us at **security@kezense.com**
2. Provide a brief description of the vulnerability.
3. Provide instructions to reproduce the issue.

We will acknowledge your report within 48 hours, and provide an estimated timeline for the fix and disclosure.

## Security Practices

We enforce:
- **Least Privilege:** Strict IAM policies across all AWS deployments.
- **Network Isolation:** Private VPC subnets for all inference and compute instances.
- **Dependency Scanning:** Automated container and pip package scanning via Amazon Inspector/Dependabot.
- **Code Review:** Mandatory PR reviews with static code analysis.
