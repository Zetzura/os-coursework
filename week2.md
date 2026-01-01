# Week 2 – Security Planning

## Threat Model

| Threat | Risk Level | Mitigation |
|------|-----------|-----------|
| SSH brute-force | High | SSH keys + Fail2Ban |
| Unauthorised access | Medium | Firewall |
| Unpatched software | Medium | Automatic updates |
| Privilege abuse | Low | sudo restrictions |

## Security Strategy
The system uses layered security including authentication hardening, firewall rules, and automated updates to minimise attack surface.
