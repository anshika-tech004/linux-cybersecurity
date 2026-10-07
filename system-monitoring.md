      - «Note: Detailed process monitoring was covered separately using commands such as "ps", "top", "pstree", and "pgrep". This file focuses on system-level monitoring and resource usage.»

---

## System Monitoring:
System monitoring helps a user observe:-
- CPU usage
- Memory usage
- Disk usage
- Running processes
- Basic system information

#  CPU Usage

CPU usage shows how much of the processor is currently being used by the system and its applications.
High CPU usage can be caused by:
- Background processes
- System tasks
- A malfunctioning process
- In some cases, suspicious or malicious activity
   Command :top
  
   # Cybersecurity Relevance
       Unexpectedly high CPU usage can be a reason to investigate which process is consuming the resources.

---

# Memory Usage

Memory (RAM) is used by the operating system and running applications.
Monitoring memory helps determine how much RAM is:
- Used
- Free
- Available
- Allocated to buffers/cache

Command: free -h

 # Cybersecurity Relevance
     Unexpectedly high memory usage may require investigation of the applications or processes using the memory.

---

# 3. Disk Usage

Disk monitoring shows how much storage space is being used and how much remains available.
A system with insufficient disk space may experience:
- Application failures
- Logging problems
- System performance issues

Command: df -h


