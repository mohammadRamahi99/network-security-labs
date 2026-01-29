## Objective
The objective of this lab was to gain hands-on experience managing and securing a Linux host system.  
This included file and directory management, user and group administration, permission controls, and system logging.

---

## Environment
- Debian Linux (Netlab environment)
- Bash shell
- sudo-enabled student account

---

## Key Skills Demonstrated

### 🔹 File & Directory Management
- Created and managed files and directories using `touch`, `mkdir`, `cp`, `mv`, and `rm`
- Navigated the filesystem using absolute and relative paths
- Used `ls` with advanced flags (`-l`, `-t`) to analyze file metadata
- Identified file types using the `file` command

### 🔹 User & Group Administration
- Created new users using `adduser`
- Managed privileges using `sudo` and the `wheel` group
- Analyzed user and group identifiers (`uid`, `gid`)
- Modified group membership using `gpasswd`
- Renamed and managed groups using `groupadd` and `groupmod`

### 🔹 File Permissions & Ownership
- Interpreted Linux permission strings (`rwx`)
- Modified permissions using `chmod`
- Changed ownership with `chown` and `chgrp`
- Demonstrated access control differences between owners, groups, and others

### 🔹 Command-Line Text Processing
- Used `cat`, `less`, `head`, and `tail` to inspect files
- Filtered output using pipes (`|`) and `grep`
- Redirected output using `>` to create new files

---

## Logging & Auditing

- Analyzed authentication logs in `/var/log/auth.log`
- Identified failed privilege escalation attempts
- Verified that `sudo` commands are logged for auditing
- Examined logging rules in `rsyslog.conf`
- Generated custom log entries using `logger`
- Inspected system logs using `journalctl`
- Verified system time configuration using `timedatectl`

---

## Security Concepts Applied
- Principle of least privilege
- Separation of users and administrative access
- Importance of accurate timestamps in log analysis
- Host-level auditing and accountability

---

## Results
- Lab completed successfully and submitted for grading
- Demonstrated secure Linux host administration practices


---

## Key Takeaways
- Host-based security is foundational to system defense
- Proper permission management prevents unauthorized access
- Logs are critical for detecting misuse and troubleshooting incidents
- Linux command-line proficiency is essential for security operations


## Evidence
Screenshots from my lab environment showing command execution and results.
<img width="814" height="275" alt="Screenshot 2026-01-29 at 4 34 23 PM" src="https://github.com/user-attachments/assets/8e76fcc5-7805-4d24-bdb5-29bb0120a00e" />


<img width="817" height="96" alt="Screenshot 2026-01-29 at 4 37 20 PM" src="https://github.com/user-attachments/assets/a93f382c-60fc-431b-ace3-3629f787d654" />


<img width="813" height="296" alt="Screenshot 2026-01-29 at 4 40 33 PM" src="https://github.com/user-attachments/assets/bd4a82c7-f5c5-4766-a554-df3540001169" />





