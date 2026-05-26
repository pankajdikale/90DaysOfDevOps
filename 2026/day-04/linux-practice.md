# Day 04 – Linux Practice: Processes and Services

## Process Checks

### 1. Check Running Processes

Command:
```bash
ps aux
```

Purpose:
Shows all running processes in the system.

---

### 2. Live Process Monitoring

Command:
```bash
top
```

Purpose:
Displays live CPU and memory usage of processes.

---

# Service Checks

### 3. Check SSH Service Status

Command:
```bash
systemctl status ssh
```

Purpose:
Checks whether SSH service is running correctly.

Observation:
Service was active and running.

---

### 4. List Running Services

Command:
```bash
systemctl list-units --type=service
```

Purpose:
Lists active services managed by systemd.

---

# Log Checks

### 5. View SSH Service Logs

Command:
```bash
journalctl -u ssh
```

Purpose:
Displays logs related to SSH service.

---

### 6. View Recent System Logs

Command:
```bash
tail -n 50 /var/log/syslog
```

Purpose:
Shows last 50 lines of system logs.

---

# Mini Troubleshooting Flow

## Scenario
Verify whether SSH service is working properly.

## Steps

### Step 1
Check service status:
```bash
systemctl status ssh
```

### Step 2
Check running SSH process:
```bash
ps aux | grep ssh
```

### Step 3
Inspect SSH logs:
```bash
journalctl -u ssh
```

## Result
SSH service was running successfully without errors.

---

# What I Learned

- How to inspect running Linux processes
- How to monitor CPU and memory usage
- How systemd services are managed
- How to inspect logs for troubleshooting
- Basic Linux troubleshooting workflow

---

# Day 04 Summary

Today I practiced:
- Linux process management
- Service inspection
- Log monitoring
- Basic troubleshooting

This hands-on practice improved my Linux command confidence and troubleshooting understanding.

#90DaysOfDevOps #DevOpsKaJosh #TrainWithShubham
