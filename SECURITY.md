# Security Policy

## Reporting Security Vulnerabilities

We take the security of GitHub projects seriously. If you believe you've found a security vulnerability, please report it to us responsibly.

### For Bug Bounty Eligible Repositories

GitHub's [Bug Bounty program](https://bounty.github.com) rewards researchers for discovering security vulnerabilities in eligible repositories.

**Steps to report:**

1. **Check eligibility** - Review the [full list of eligible projects](https://bounty.github.com/#scope) on our Bug Bounty site
2. **Submit via HackerOne** - If eligible, submit your report through [HackerOne](https://hackerone.com/github)
3. **Review guidelines** - Familiarize yourself with our [rules](https://bounty.github.com/#rules) and [FAQ](https://bounty.github.com/#faqs)

**What to include in your report:**

- Clear description of the vulnerability
- Steps to reproduce the issue
- Potential impact and severity assessment
- Proof of concept (if applicable)
- Suggested remediation (optional)

### For Non-Bug Bounty Repositories

For repositories not covered by the Bug Bounty program:

- **Open a security advisory** - Use GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability) feature if available
- **Open an issue** - Create a new issue in the repository
- **Contact maintainers** - Reach out to repository maintainers directly if the vulnerability is critical

**Important:** Please do not disclose security vulnerabilities publicly until they have been addressed.

## Security Best Practices

When contributing to GitHub repositories:

- **Keep dependencies updated** - Regularly update to patched versions
- **Review dependency alerts** - Address Dependabot security alerts promptly
- **Follow secure coding practices** - Avoid common vulnerabilities (XSS, SQL injection, etc.)
- **Protect sensitive data** - Never commit secrets, tokens, or credentials
- **Use least privilege** - Request minimal necessary permissions

## Response Process

When you report a vulnerability:

1. **Acknowledgment** - We'll acknowledge receipt of your report
2. **Assessment** - Our security team will assess the vulnerability
3. **Remediation** - We'll work on a fix and coordinate disclosure timing
4. **Recognition** - We'll credit you for responsible disclosure (if desired)
5. **Resolution** - We'll notify you when the issue is resolved

## Scope

### In Scope

- Security vulnerabilities in code
- Authentication and authorization issues
- Data exposure or leakage
- Injection vulnerabilities
- Cross-site scripting (XSS)
- Cross-site request forgery (CSRF)
- Server-side request forgery (SSRF)

### Out of Scope

- Vulnerabilities in third-party dependencies (report to the dependency maintainer)
- Social engineering attacks
- Denial of service attacks
- Issues requiring extensive user interaction
- Theoretical vulnerabilities without proof of concept

## Additional Resources

- [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories)
- [Dependabot Security Updates](https://docs.github.com/en/code-security/dependabot/dependabot-security-updates)
- [Security Best Practices](https://docs.github.com/en/code-security/getting-started/securing-your-organization)

Thank you for helping keep GitHub and our community safe!
