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

# Week 2: System Administration & User Management

## Task 1: System Updates and Maintenance
The first step in securing the server was to ensure all software and security patches were up to date.
- **Command:** `sudo apt update && sudo apt upgrade -y`

![System Updates](images/week-2-evidence-1.png)
*Figure 1: Successful completion of system updates.*

---

## Task 2: User Management
I created a new administrative user to demonstrate proper access control and to avoid using the primary account for daily tasks.
- **New User:** `manager`
- **Action:** Added the user to the `sudo` group to grant administrative privileges.

![Creating User](images/week-2-evidence-2.png)
*Figure 2: Creating the 'manager' account.*

![Verifying Admin Rights](images/week-2-evidence-3.png)
*Figure 3: Verification that 'manager' has sudo permissions via the 'groups' command.*

---

## Task 3: Security Audit
I performed a basic login audit to verify who has accessed the system and ensure the login history is being recorded correctly.
- **Command:** `last -a`

![System Audit](images/week-2-evidence-4.png)
*Figure 4: System login history showing an audit trail of user activity.*
