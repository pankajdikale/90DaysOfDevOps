# Day 04 – Linux Practice: Processes and Services

## Introduction

Today I practiced Linux process management, systemd services, and log inspection using real Linux commands.

This hands-on practice helped me understand how Linux systems are monitored and troubleshooted in DevOps environments.

---

# Process Checks

## 1. Check Running Processes

### Command
```bash
ps aux
```

### Purpose
Shows all running processes in the system.

---

## 2. Live Process Monitoring

### Command
```bash
top
```

### Purpose
Displays live CPU and memory usage of running processes.

---

# Service Checks

## 3. Check Cron Service Status

### Command
```bash
systemctl status cron
```

### Purpose
Checks whether cron service is running properly.

### Observation
The service was active and running.

---

## 4. List Running Services

### Command
```bash
systemctl list-units --type=service
```

### Purpose
Lists active systemd services running on the system.

---

# Log Checks

## 5. Check Cron Service Logs

### Command
```bash
journalctl -u cron
```

### Purpose
Displays logs related to cron service.

---

## 6. View Recent System Logs

### Command
```bash
tail -n 50 /var/log/syslog
```

### Purpose
Shows last 50 lines of system logs.

---

# Mini Troubleshooting Practice

## Scenario
I wanted to verify whether the cron service was working correctly.

## Troubleshooting Steps

### Step 1
Checked service status:
```bash
systemctl status cron
```

### Step 2
Verified running process:
```bash
ps aux | grep cron
```

### Step 3
Checked logs:
```bash
journalctl -u cron
```

### Result
Cron service was running successfully without errors.

---

# What I Learned

- How to inspect running Linux processes
- How to monitor CPU and memory usage
- How systemd services are managed
- How to inspect logs for troubleshooting
- Basic Linux troubleshooting workflow

---

# Why This Matters in DevOps

Linux troubleshooting is a core DevOps skill.

These commands help engineers:
- Detect service failures
- Monitor applications
- Debug issues quickly
- Reduce downtime in production systems

---

# Commands Practiced Today

| Command | Purpose |
|---|---|
| `ps aux` | Show running processes |
| `top` | Live system monitoring |
| `systemctl status cron` | Check service status |
| `systemctl list-units --type=service` | List running services |
| `journalctl -u cron` | View service logs |
| `tail -n 50 /var/log/syslog` | View recent logs |

---

# Day 04 Summary

Today I practiced:
- Linux processes
- systemd services
- Log monitoring
- Basic troubleshooting

This hands-on practice improved my Linux command confidence and troubleshooting understanding.

#90DaysOfDevOps #DevOpsKaJosh #TrainWithShubham
