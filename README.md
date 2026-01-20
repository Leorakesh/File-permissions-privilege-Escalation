# File-permissions-privilege-Escalation

Day 27 of 100 days challenge

Day 27 — Linux Commands, File Permissions & Privilege Escalation

On Day 27, I explored how Linux commands and file permissions play a critical role in privilege escalation. Understanding how access control works in Linux helps both attackers and defenders identify misconfigurations that can lead to unauthorized root access.

What I Learned

Linux permissions define who can read (r), write (w), and execute (x) files and directories. When these are misconfigured, they can allow users to escalate privileges.

Key concepts covered:

Understanding permission structure: rwx r-x r--

File ownership: user, group, others

Special permissions: SUID, SGID, Sticky Bit

Using commands like ls -l, chmod, chown, id, groups

Finding misconfigured binaries for escalation

How attackers abuse writable files and SUID programs

Common Privilege Escalation Techniques

Exploiting SUID binaries

Abusing writable system files

Misconfigured cron jobs

Weak file ownership settings

Insecure scripts run as root
