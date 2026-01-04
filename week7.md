# Week 7 – Data Backup & Recovery

## 1. Objective
The final week focused on implementing a basic data backup strategy. Creating archives of system documentation is a critical administrative task to prevent data loss.

## 2. Creating a System Archive
I utilized the `tar` (Tape Archive) utility to compress all my weekly markdown documentation into a single, portable archive file.
* **Command used:** `tar -cvzf ~/backups/os_journal_final.tar.gz *.md`

## 3. Verifying the Backup
I verified that the backup file was successfully created in the dedicated backup directory and checked its file size.
* **Command used:** `ls -lh ~/backups`

![Backup Verification](./images/week-7-evidence-1.png)
*Above: Terminal output showing the successful creation of the compressed backup archive.*

## 4. Project Wrap-up
This concludes the 7-week deployment and configuration of the Ubuntu 24.04 LTS Server. All technical milestones have been achieved and documented.

---
[Back to Home](./index.html)
