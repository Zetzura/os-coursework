---

### 📄 `week4.md`
*(Copy and paste this exact text)*

```markdown
# Week 4 – System Configuration & Hardening
```
## SSH Configuration
The SSH daemon was hardened by editing the configuration file:
```bash
sudo nano /etc/ssh/sshd_config
```
Changes made:

PermitRootLogin no (Prevents direct root access)

PasswordAuthentication no (Forces use of SSH keys)

Restarted SSH:

## Firewall Configuration
sudo ufw allow OpenSSH
sudo ufw enable
sudo ufw status

This ensures only secure remote access is allowed.
