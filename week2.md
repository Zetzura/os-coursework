# Week 2 – Security Planning & User Management

## 1. Security Strategy
This week focused on implementing the **Principle of Least Privilege**. By creating a dedicated user for administration and restricting the 'root' account, we reduce the attack surface of the server.

## 2. Administrative User Creation
I created a primary user named `zetzura` to handle all system tasks.

![Creating the User](./images/week-2-evidence-1.png)
*Above: Documentation of the user creation process and initial setup.*

## 3. Privilege Management (Sudo)
To perform administrative tasks without logging in as root, the `zetzura` user was added to the **sudo** group.

![Sudo Group Verification](./images/week-2-evidence-2.png)
*Above: Verifying that the user has been granted appropriate administrative permissions.*

## 4. System Cleanup & Security Hardening
As part of system hygiene, I audited existing accounts and removed temporary test users that were no longer required.

![Deleting Test Users](./images/week-2-evidence-3.png)
*Above: Removing the 'manager' account to secure the user environment.*

## 5. Final User Audit
A final check of the `/etc/passwd` file and group assignments confirms that only authorized users have access to the system.

![Final User Check](./images/week-2-evidence-4.png)

---
[Back to Home](./index.html)
