# Week 4 – Software Installation & Final Review

## 1. Project Completion
The final phase of the server setup involved installing essential software tools and performing a final system audit to ensure all configurations from previous weeks remained stable.

## 2. Software Installation
I installed the following packages to enhance the server's functionality and monitoring capabilities.

### A. System Information Tool (Neofetch)
To provide a clear overview of the OS and hardware in the terminal, I installed Neofetch.
* **Command used:** `sudo apt install neofetch -y`

![System Overview](./images/week-4-evidence-1.png)
*Above: Neofetch output showing the Ubuntu 24.04 LTS logo and system specs.*

### B. Web Server Setup (Optional/Verification)
I verified the status of the system's package manager to ensure it was fully updated and ready for future application deployments.
* **Command used:** `sudo apt update && sudo apt upgrade -y`

![Update Verification](./images/week-4-evidence-2.png)
*Above: Screenshot confirming the system is up to date and all packages are current.*

## 3. Final Resource Audit
I used the `df -h` and `free -h` commands one last time to ensure that the software installations did not over-encumber the allocated 2GB of RAM.

![Resource Check](./images/week-4-evidence-3.png)

## 4. Conclusion
Over the last four weeks, I have successfully:
1. Deployed a headless **Ubuntu 24.04 LTS** server.
2. Secured the system by creating a **Sudo user** (`zetzura`) and removing test accounts.
3. Enabled **Remote Access via SSH** and secured it with **UFW**.
4. Verified system stability and installed monitoring tools.

The server is now fully operational and ready for a production workload.

---
[Back to Home](./index.html)
