# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Which versions are eligible for receiving such patches depends on the CVSS v3.0 Rating:

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via email to [security@saipienlabs.com](mailto:security@saipienlabs.com).

You should receive a response within 48 hours. If for some reason you do not, please follow up via email to ensure we received your original message.

Please include the following information (as much as you can provide) to help us better understand the nature and scope of the possible issue:

- Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

## Preferred Languages

We prefer all communications to be in English.

## Security Update Policy

When we learn of a critical security issue, we will:

1. Confirm the vulnerability and determine affected versions
2. Audit code to find similar problems
3. Prepare fixes for all supported releases
4. Release patched versions and notify users

## Bug Bounty Program

We do not currently offer a bug bounty program. However, we greatly appreciate the security research community's efforts in helping us keep wellstead secure.

## Security-Related Configuration

For production deployments, please ensure:

- All secrets are stored in environment variables, never committed to code
- Rate limiting is enabled for all public APIs
- HTTPS/TLS is enforced for all connections
- Regular dependency updates via Dependabot
- CodeQL scanning is enabled (automatic on this repo)

## Contact

For general security questions not related to vulnerabilities, contact [hello@saipienlabs.com](mailto:hello@saipienlabs.com).
