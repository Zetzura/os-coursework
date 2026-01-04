# Week 2 – Security Planning & User Management

## 1. Security Strategy
This week, I implemented the **Principle of Least Privilege**. By creating a dedicated user for administration and restricting 'root' usage, we ensure that the system is more secure against accidental or unauthorized changes.

## 2. User Creation & Group Management
I created a primary administrative account to handle system maintenance.

### Tasks Performed:
- **Created Administrative User:** Set up the `zetzura` account.
- **Assigned Privileges:** Added the user to the `sudo` group to enable administrative commands.
- **System Hygiene:** Removed the temporary `manager` account to prevent unnecessary access points.

## 3. Evidence of Implementation
Below is the visual documentation of the security steps taken during this phase.

### A. Creating the User
![User Creation](./images/week-2-evidence-1.png)
*Creating the 'zetzura' user and setting initial parameters.*

### B. Adding to Sudo Group
![Sudo Verification](./images/week-2-evidence-2.png)
*Granting 'zetzura' administrative rights via the sudo group.*

### C. Removing Test Accounts
![Deleting Manager](./images/week-2-evidence-3.png)
*Deleting the 'manager' account to secure the system.*

### D. Final User Verification
![System Audit](./images/week-2-evidence-4.png)
*Final check confirming 'zetzura' is correctly configured in the system groups.*

---
[Back to Home](./index.html)
