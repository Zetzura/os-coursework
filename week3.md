Markdown

# Week 3 – Application Selection

## Monitoring Tools Used
The following industry-standard tools were selected for system administration:

| Tool | Purpose |
|----|----|
| **htop** | Real-time interactive CPU and memory usage |
| **vmstat** | System performance statistics |
| **iostat** | Disk Input/Output monitoring |
| **iperf3** | Network bandwidth testing |

## Installation
The tools were installed using the package manager:
```bash
sudo apt update
sudo apt install htop sysstat iperf3 -y
```
These tools allow continuous monitoring and performance evaluation.

# Week 3 – Remote Access & System Hardening

## Technical Implementation
This week I configured remote access to the server and implemented initial security hardening.

### 1. SSH Configuration
I installed and enabled the OpenSSH server to allow for remote management.
* **Command:** `sudo apt install openssh-server -y`
* **Status:** Verified as "active (running)".

![SSH Status](images/week-3-evidence-1.png)

### 2. Remote Access via Port Forwarding
Because the server is on a NAT network, I configured Port Forwarding (Port 2222 -> 22) in VirtualBox to connect via Windows PowerShell.
* **Connection String:** `ssh zetzura@127.0.0.1 -p 2222`

![Remote Access Connection](images/week-3-evidence-3.png)

### 3. Firewall Security (UFW)
I enabled the Uncomplicated Firewall to block all traffic except for SSH to ensure the server is not exposed to unauthorized access.
* **Command:** `sudo ufw allow ssh` && `sudo ufw enable`

![Firewall Status](images/week-3-evidence-4.png)
