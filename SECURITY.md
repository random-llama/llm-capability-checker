# Security Policy

## 🔒 Our Commitment to Security

We take the security of LLM Capability Checker seriously. Even though this is a local-only application with no network communication (except model database downloads), we want to ensure it's safe for everyone to use.

## 🛡️ What We Do to Stay Secure

### Privacy-First Design
- **No telemetry or tracking** - We don't collect any user data
- **Local-only operation** - All processing happens on your machine
- **No account required** - No authentication or user databases
- **No external APIs** - Except for downloading the model database from GitHub
- **Open source** - Full transparency, audit the code yourself

### Secure Development Practices
- Regular dependency updates
- Code reviews for all contributions
- Automated security scanning (planned)
- Following .NET security best practices
- Minimal external dependencies

### Data Storage
- All user data stored locally on your machine
- No cloud storage or external servers
- User settings stored in standard app data directories
- No sensitive information collected or stored

## 🐛 Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | ❌ No (archived)   |
| < 1.0   | ❌ Not released    |

This project is archived. No versions are supported and no security updates will be released.

## 🚨 Reporting a Vulnerability

**This project is archived. Vulnerability reports are not monitored and no fixes will be released.** Do not use this app for security-sensitive work.

### What to Include

Please include the following information:

- **Description**: Clear description of the vulnerability
- **Type**: Category (e.g., XSS, SQL injection, privilege escalation)
- **Location**: File path and line number if applicable
- **Impact**: What an attacker could do with this vulnerability
- **Reproduction**: Step-by-step instructions to reproduce
- **Proof of Concept**: Code or screenshots demonstrating the issue
- **Suggested Fix**: If you have ideas on how to fix it (optional)
- **Your Contact Info**: How we can reach you for follow-up

### What to Expect

After you submit a report:

1. **Acknowledgment**: We'll acknowledge receipt within **48 hours**
2. **Assessment**: We'll investigate and assess severity within **7 days**
3. **Updates**: We'll keep you informed of our progress
4. **Fix**: We'll develop and test a fix
5. **Disclosure**: We'll coordinate public disclosure timing with you
6. **Credit**: We'll credit you in the security advisory (if you wish)

### Response Timeline

- **Critical**: 24-48 hours for initial response, fix within 7 days
- **High**: 48-72 hours for initial response, fix within 14 days
- **Medium**: 7 days for response, fix within 30 days
- **Low**: 14 days for response, fix in next release

## 🏆 Security Hall of Fame

We recognize security researchers who help us keep LLM Capability Checker secure:

<!-- Security researchers will be listed here after responsible disclosure -->

*No security vulnerabilities have been reported yet.*

## 🔐 Scope

### In Scope

The following are within the scope of our security policy:

- ✅ The main application (LLMCapabilityChecker)
- ✅ Build and deployment scripts
- ✅ Dependencies and third-party libraries
- ✅ Data handling and storage
- ✅ File system access and permissions
- ✅ Model database downloads

### Out of Scope

The following are NOT considered security vulnerabilities:

- ❌ Issues requiring physical access to the user's machine
- ❌ Social engineering attacks
- ❌ Denial of service (DOS) by local resource exhaustion
- ❌ Security issues in third-party applications or operating systems
- ❌ Issues already publicly disclosed
- ❌ Issues requiring highly unlikely user interaction
- ❌ Vulnerabilities in outdated/unsupported versions

## 🔍 Known Security Considerations

### Data Privacy
- **User data is local**: All settings and data stored on user's machine
- **No cloud sync**: We don't sync data to any servers
- **File permissions**: App respects OS file permissions

### Network Security
- **HTTPS only**: Model database downloaded over HTTPS from GitHub
- **No credentials**: No API keys or passwords transmitted
- **Certificate validation**: Standard .NET certificate validation

### System Access
- **Read-only hardware detection**: We only read system information
- **User-level permissions**: No admin/root access required
- **Standard directories**: Uses OS-standard app data directories

## 🛠️ Security Features

### Current
- HTTPS-only downloads
- No external API calls (except model database)
- Local-only data storage
- No user authentication or accounts
- Open source for transparency

### Planned
- Automated dependency scanning
- Code signing for releases
- Security audit by third party
- Bug bounty program (when budget allows)

## 📚 Security Resources

### For Users
- **Privacy**: See our privacy commitment in [README.md](README.md#-privacy)
- **Data Storage**: Learn where your data is stored in [FAQ.md](docs/FAQ.md)
- **Safe Usage**: Tips for secure usage in [USER_GUIDE.md](docs/USER_GUIDE.md)

### For Developers
- **Secure Coding**: Guidelines in [CONTRIBUTING.md](CONTRIBUTING.md)
- **.NET Security**: [Microsoft Security Best Practices](https://learn.microsoft.com/en-us/dotnet/standard/security/)
- **Dependency Management**: Keep dependencies updated

## 🤝 Responsible Disclosure

We appreciate security researchers who practice responsible disclosure:

1. **Report privately** first - Give us time to fix before public disclosure
2. **Reasonable timeline** - Allow at least 90 days for us to address the issue
3. **Coordinated disclosure** - Work with us on disclosure timing
4. **No exploitation** - Don't exploit the vulnerability beyond proving it exists
5. **Good faith** - Don't access others' data or disrupt the service

We commit to:

1. **Timely response** - Acknowledge reports quickly
2. **Transparent process** - Keep you informed of progress
3. **Credit and recognition** - Publicly acknowledge your contribution (if desired)
4. **No legal action** - We won't pursue legal action against good-faith researchers

## 📄 Legal Safe Harbor

We consider security research conducted in accordance with this policy to be:

- **Authorized** concerning the Computer Fraud and Abuse Act
- **Authorized** concerning our Terms of Service (when we have them)
- **Exempt** from the Digital Millennium Copyright Act

We will not pursue legal action against security researchers who:
- Follow this security policy
- Report vulnerabilities responsibly
- Act in good faith
- Don't harm users or the project

## 📞 Contact

This project is archived. There is no active contact or support channel.

## 🙏 Thank You

Thank you for helping keep LLM Capability Checker and its users safe!

Security researchers play a crucial role in protecting open source software. We deeply appreciate your efforts and expertise.

---

**Last Updated**: October 2025

**Version**: 1.0
