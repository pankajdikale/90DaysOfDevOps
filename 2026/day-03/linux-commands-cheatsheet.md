# Day 03 – Linux Commands Cheat Sheet

## Introduction
Today I practiced important Linux commands used in DevOps and system administration.

This cheat sheet contains commands for:

- Process Management
- File System Navigation
- Networking Troubleshooting
- Log Monitoring

---

# Process Management Commands

| Command | Usage |
|---|---|
| `ps aux` | Show all running processes |
| `top` | Live process monitoring |
| `htop` | Interactive process viewer |
| `kill PID` | Stop a process using PID |
| `killall process_name` | Kill process by name |
| `jobs` | Show background jobs |
| `bg` | Run job in background |
| `fg` | Bring job to foreground |
| `uptime` | Show system uptime |
| `nice` | Start process with priority |

---

# File System Commands

| Command | Usage |
|---|---|
| `pwd` | Show current directory |
| `ls -la` | List all files with details |
| `cd folder` | Change directory |
| `mkdir folder` | Create new folder |
| `touch file.txt` | Create empty file |
| `cat file.txt` | View file contents |
| `cp file1 file2` | Copy file |
| `mv old new` | Move or rename file |
| `rm file.txt` | Delete file |
| `find . -name file` | Search for files |
| `df -h` | Show disk usage |
| `du -sh folder` | Show folder size |
| `chmod +x file.sh` | Give execute permission |
| `chown user:user file` | Change file ownership |

---

# Networking Commands

| Command | Usage |
|---|---|
| `ping google.com` | Check internet connectivity |
| `ip addr` | Show IP address |
| `curl https://example.com` | Fetch website data |
| `dig google.com` | DNS lookup |
| `ss -tulnp` | Show listening ports |
| `traceroute google.com` | Trace network route |
| `wget URL` | Download files |

---

# Log & Monitoring Commands

| Command | Usage |
|---|---|
| `tail -f logfile` | Monitor logs live |
| `journalctl -xe` | View system logs |
| `free -h` | Show memory usage |
| `uname -a` | Show system information |
| `whoami` | Show current user |

---

# Commands I Practiced Today

## 1. pwd
- Shows current directory
- Helps avoid working in wrong location

## 2. ls
- Lists files and folders
- Useful for checking server contents

## 3. cd
- Navigates between directories
- Important for accessing logs and configs

## 4. ping
- Tests network connectivity
- Useful during troubleshooting

## 5. tail -f
- Shows live log updates
- Helps monitor application issues

---

# Why These Commands Matter in DevOps

Linux commands are essential for:

- Troubleshooting servers
- Monitoring applications
- Managing processes
- Inspecting logs
- Fixing networking issues

Fast command-line troubleshooting helps reduce downtime and restore services quickly.

---

# Favorite Commands

- `tail -f` → Live log monitoring
- `ping` → Network testing
- `top` → System performance monitoring

---

# Day 03 Summary

Today I improved my Linux command-line skills by practicing commands related to:

- Process Management
- File System Navigation
- Networking
- System Monitoring

Learning Linux step by step is helping me build a strong DevOps foundation.

#90DaysOfDevOps #DevOpsKaJosh #TrainWithShubham
