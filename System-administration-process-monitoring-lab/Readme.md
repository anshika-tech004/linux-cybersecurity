## Project Overview
This practical lab documents my hands on practice with linux process monitoring, system administration, service management and basic troubleshooting using Ubuntu Linux.

## Objectives

- Identify and inspect running processes.
- Monitor system activity and resource usage.
- Practise basic file and directory monitoring.
- Check the status of Linux services.
- Install and verify a software package.
- Check disk usage, memory usage, and basic system information.
- View and search relevant system logs.
- Document practical work with terminal screenshots and observations.

## Lab Environment

- Operating System: Ubuntu Linux
- Interface: Linux Terminal
- Shell: Bash
- Tools: Standard Linux command-line utilities, "systemctl", APT, and "journalctl"

## Practical Exercises

  # Task 1: Finding and Monitoring Processes

- Objective: Identify running processes and understand their resource usage.
- Commands:
    - ps
    - ps aux
    - top
    - pstree
    - pgrep sleep

- To practise background process management:
   - sleep 300 &
   - jobs
   - pgrep -a sleep

  # Task 2: Basic File and Directory Monitoring

- Objective: Practise inspecting files and directories and checking file information.
- Commands:
   - pwd
   - ls -lah
   - stat README.md

  # Task 3: Checking a Linux Service

- Objective: Inspect a service and understand its current status.
- Commands:
   - systemctl --type=service --state=running
   - systemctl status cron

 # Task 4: Installing a Software Package

- Objective: Learn how Ubuntu manages software packages using APT.

# Task 5: Checking Disk, Memory, and System Information

- Objective: Inspect system resources and basic system information.
- Commands:
   - df -h
   - free -h
   - uptime
   - uname -a

# Task 6: Viewing Relevant Linux Logs

- Objective: Learn how to view and search system logs for basic troubleshooting.
- Commands:
   - journalctl -n 20
   - journalctl --since "1 hour ago"
- Note: This exercise focuses on basic log viewing and searching, not advanced security incident investigation.

##  Key Learnings

This lab is intended to develop practical familiarity with:

- Linux process identification and monitoring.
- File inspection and basic change tracking.
- Service status inspection.
- Package installation and verification.
- Disk, memory, and system monitoring.
- Basic system log inspection and troubleshooting.

- These skills provide a foundation for Linux administration and cybersecurity, where understanding normal system activity is important.

## Conclusion
The exercises and their documented outputs will serve as evidence of my ongoing Linux learning and provide a foundation for more advanced Linux security and cybersecurity labs.

