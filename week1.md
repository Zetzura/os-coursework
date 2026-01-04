# Week 1 – System Planning and Architecture

## Overview
A headless Ubuntu Server 24.04 LTS system was deployed to simulate a real-world server environment. The system is accessed remotely using SSH from a workstation.

## System Information
Commands used to verify the system:

```
bash
uname -a
lsb_release -a
free -h
df -h
ip a
```
## Architecture
- **Operating System:** Ubuntu Server 24.04 LTS
- **Access Method:** SSH (Secure Shell)
- **Interface:** Command-line only (Headless)
- **Network:** Private virtual network

## Justification
Ubuntu Server was selected due to its stability, long-term support (LTS), and strong security features.

## System Verification
The following screenshot confirms the successful installation and configuration of the Ubuntu 24.04 LTS server.

![System Verification Evidence](images/week1-proof.png)

### Verification Observations:
- **OS:** Ubuntu 24.04.3 LTS (Noble Numbat)
- **Kernel:** 6.8.0-90-generic
- **Memory:** 1.9Gi total recognized
- **Storage:** 25GB root partition
