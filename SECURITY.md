# VorzixDev Security Policy and Responsible Disclosure

## 1. Reporting a Vulnerability

Do not report a security vulnerability through a public issue, discussion, pull request, social post, or public Discord channel.

Send reports privately to **vorzixdev.official@gmail.com** with the subject:

`Security Report - [Product or Repository Name]`

If a repository supports private vulnerability reporting or GitHub Security Advisories, that private channel may also be used.

## 2. Information to Include

Provide only the information necessary to investigate:

- Affected product, repository, component, and version
- Clear description of the issue
- Reproduction steps or proof of concept
- Expected and actual behavior
- Potential impact
- Relevant logs, screenshots, or video with secrets removed
- Suggested mitigation, if available
- Whether the issue has been disclosed elsewhere

Do not send passwords, session cookies, full customer records, payment credentials, government identification, or unrelated personal data.

## 3. Responsible Testing Rules

Security research must not:

- Access, modify, or delete data that does not belong to the reporter.
- Disrupt services, users, stores, games, repositories, or infrastructure.
- Use social engineering, credential theft, malware, denial of service, or destructive testing.
- Attempt to profit from stolen data or unauthorized access.
- Publicly disclose the issue before coordinated review.
- Expand testing beyond the minimum required to demonstrate the problem.

Stop testing and report immediately if sensitive information, credentials, customer data, or unintended access is encountered.

## 4. Credentials and Secrets

Never commit or share:

- Roblox cookies or authentication tokens
- GitHub tokens, SSH private keys, or signing keys
- Discord bot tokens or webhook secrets
- API keys or database credentials
- Payment-provider credentials
- Recovery codes or session tokens

If a secret is exposed, revoke or rotate it immediately and report the incident privately.

## 5. Supported Versions

Security support is defined separately for each released product or repository. Check the relevant product documentation or release notes.

Unreleased builds, modified customer copies, unsupported forks, or end-of-support versions may receive limited or no security maintenance unless separately agreed.

## 6. Response Process

VorzixDev may:

1. Acknowledge the report
2. Request clarification or evidence
3. Reproduce and assess the issue
4. Develop and test a fix
5. Coordinate release and disclosure
6. Publish a security advisory when appropriate

Response and resolution time depend on severity, reproducibility, product status, contributor availability, and platform requirements. No fixed response or fix time is guaranteed by this public policy.

## 7. Recognition and Compensation

VorzixDev may credit good-faith reporters when appropriate and permitted. This policy does not create a bug-bounty program, payment obligation, revenue-share right, employment relationship, or guarantee of public recognition.

## 8. Scope

This policy applies to VorzixDev-controlled repositories, released products, and official services unless a repository or product publishes a more specific security policy.
