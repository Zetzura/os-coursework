# Week 1 – System Planning and Architecture

## 1. Project Overview
A headless Ubuntu Server 24.04 LTS system was deployed to simulate a real-world server environment. The system is designed to be accessed remotely using SSH from a Windows workstation.

## 2. System Architecture
I have allocated the following resources to the Virtual Machine to ensure a balance between server performance and host stability.

| Component         | Specification                | Rationale                                     |
| :---------------- | :--------------------------- | :-------------------------------------------- |
| **Operating System** | Ubuntu Server 24.04 LTS      | Chosen for stability and long-term support.   |
| **CPU** | 1 Virtual Core               | Sufficient for headless server operations.    |
| **RAM** | 2 GB                         | Minimum required for stable 24.04 operation.  |
| **Storage** | 25 GB (Dynamically Allocated)| Efficient use of physical host disk space.    |
| **Network** | NAT                          | Allows the VM to access the internet safely.  |

## 3. System Verification
The following screenshot confirms the successful installation and initial resource verification of the Ubuntu 24.04 LTS server.

![System Verification](./images/week-1-evidence.png)

### Verification Observations:
- **Kernel:** 6.8.0-90-generic
- **Memory:** 1.9Gi total recognized
- **Storage:** 25GB root partition
- **Status:** OS updated using `sudo apt update && sudo apt upgrade -y`

---
[Back to Home](./index.html)
