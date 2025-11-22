# Security Policy

## 🎮 Project Context

AntiPattern Bird is a **single-player desktop game** with no network connectivity, 
no data collection, and no user authentication. Security risks are minimal, but we 
still follow best practices.

## 📦 Supported Versions

| Version | Supported          | Notes |
| ------- | ------------------ | ----- |
| Latest release | :white_check_mark: | Always recommended |
| Older releases | :x: | Security fixes only in latest |
| Development branch | :warning: | Use at your own risk |


## 🛡️ Security Considerations

### What This Game Does
- ✅ Runs **locally** on your machine (internet required to reach shared common internet resources)
- ✅ **No data collection** or telemetry
- ✅ **No external dependencies** at runtime

### What This Game Does NOT Do
- ❌ No network connections
- ❌ No file system writes
- ❌ No execution of external code
- ❌ No personal data handling


## 🐛 Reporting a Vulnerability

If you discover a security issue, please report it responsibly:

### For Critical Issues (RCE, arbitrary code execution, etc.)
📧 **Email:** dvdred@gmail.com  
🔒 **Please include:**
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

### For Non-Critical Issues (crashes, resource leaks, etc.)
Open a Issue with the `security` label.
