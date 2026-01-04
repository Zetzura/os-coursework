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

# Week 3: Remote Access and Security

## Task 1: Installing and Enabling SSH
I installed the OpenSSH server to allow for remote management.
- **Command:** `sudo apt install openssh-server -y`
- **Verification:** Confirmed the service is active and enabled on boot.

![SSH Status](images/week-3-evidence-1.png)

## Task 2: Remote Connection
I configured Port Forwarding in VirtualBox (Port 2222 -> 22) to allow my Windows host to communicate with the VM.
- **Connection Command:** `ssh zetzura@127.0.0.1 -p 2222`

![Remote Login](images/week-3-evidence-3.png)

## Task 3: Firewall Configuration
I enabled the Uncomplicated Firewall (UFW) to secure the server, ensuring only SSH traffic is permitted.

![Firewall Status](images/week-3-evidence-4.png)
