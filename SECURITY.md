# GitHub Security Policy

## Overview

Security is a top priority for the GitHub organization. We appreciate the security research community's efforts in helping us maintain the security of our projects.

## Reporting Security Vulnerabilities

### Bug Bounty Program

GitHub's [Bug Bounty program](https://bounty.github.com) rewards researchers for discovering security vulnerabilities in eligible repositories.

**Eligible repositories:**
- Full list available at: https://bounty.github.com/#scope
- Includes core GitHub services and select open source projects

**How to submit:**
1. Check if the repository is eligible at https://bounty.github.com/#scope
2. Submit your report via [HackerOne](https://hackerone.com/github)
3. Follow our [rules](https://bounty.github.com/#rules) and [FAQ](https://bounty.github.com/#faqs)

### Non-Bug Bounty Repositories

For repositories **not** covered by the Bug Bounty program:

1. **Open a security advisory** (preferred method)
   - Go to the repository's Security tab
   - Click "Report a vulnerability"
   - Fill out the security advisory form

2. **Open an issue** (for non-sensitive issues)
   - Use the repository's issue tracker
   - Label as "security" if possible

3. **Contact the team directly** (for sensitive issues)
   - Email: support@github.com
   - Include "SECURITY" in the subject line

## What to Include in a Security Report

To help us quickly understand and address the issue, please include:

### Required Information
- **Description**: Clear explanation of the vulnerability
- **Impact**: Potential security impact and severity
- **Reproduction steps**: Detailed steps to reproduce the issue
- **Affected versions**: Which versions are vulnerable

### Optional but Helpful
- **Proof of concept**: Code or commands demonstrating the issue
- **Suggested fix**: Ideas for how to resolve the vulnerability
- **Environment details**: OS, browser, or other relevant context
- **Screenshots/videos**: Visual evidence when applicable

### Example Report Structure

```markdown
## Vulnerability Description
[Brief description of the vulnerability]

## Impact
[What an attacker could do with this vulnerability]

## Steps to Reproduce
1. [First step]
2. [Second step]
3. [Third step]

## Affected Versions
- Version X.Y.Z
- All versions >= X.Y

## Suggested Fix
[Optional: Your recommendations]

## Additional Context
[Any other relevant information]
```

## Security Best Practices

When contributing to our repositories, please:

- **Never commit secrets**: API keys, passwords, tokens, or credentials
- **Use secure dependencies**: Keep dependencies up to date
- **Follow secure coding practices**: Input validation, output encoding, etc.
- **Review code carefully**: Look for potential security issues in PRs
- **Report don't exploit**: If you find a vulnerability, report it responsibly

## Response Timeline

For Bug Bounty submissions:
- **Initial response**: Within 2-3 business days
- **Triage**: Within 5 business days
- **Resolution timeline**: Varies by severity

For non-bounty reports:
- **Acknowledgment**: Within 5 business days
- **Updates**: As progress is made
- **Resolution**: Based on severity and complexity

## Disclosure Policy

We follow a coordinated disclosure approach:

1. **Private disclosure**: Report sent privately to maintainers
2. **Investigation**: We investigate and develop a fix
3. **Fix release**: Security patch is released
4. **Public disclosure**: Advisory published after fix is available

**Please do not:**
- Publicly disclose the vulnerability before we've had a chance to fix it
- Access or modify data that doesn't belong to you
- Perform actions that could harm the reliability of our services

## Scope and Exclusions

### In Scope
- Security vulnerabilities in code
- Authentication and authorization issues
- Data exposure or leakage
- Injection vulnerabilities (SQL, XSS, etc.)
- Cryptographic weaknesses

### Out of Scope
- Social engineering attacks
- Physical attacks
- Denial of Service (DoS/DDoS)
- Issues in third-party services
- Vulnerabilities in outdated versions (unless still supported)
- Self-XSS or issues requiring extensive user interaction

## Recognition

We value the contributions of security researchers:

- **Bug bounty rewards**: For eligible submissions via HackerOne
- **Public acknowledgment**: Credit in security advisories (if desired)
- **Hall of fame**: Recognition on our security page

## Questions?

For questions about this policy:
- Review our [Bug Bounty FAQ](https://bounty.github.com/#faqs)
- Contact us at support@github.com

Thank you for helping keep GitHub and our community safe!
