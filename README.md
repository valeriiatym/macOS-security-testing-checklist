# macOS-security-testing-checklist



# Table of Contents
- Security Settings
- Privacy Settings
- FileVault
- Firewall



# FileVault
FileVault adds an extra layer of security, beyond your admin user account password, by encrypting the entire macOS volume. This means no one can access the data on your hard drive without the decryption password.

- [ ] Verify FileVault -> `sudo fdesetup status`
