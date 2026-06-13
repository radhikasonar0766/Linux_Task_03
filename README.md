# Linux_Task_03_RadhikaSonar

## Objective
To learn process management, system monitoring, service monitoring, and basic shell scripting in Linux.

## Part A: Process Monitoring
### Commands Used
```bash
ps
ps aux
top
htop
```
## Part B: Process Management
### Commands Used
```bash
sleep 300

ps aux | grep sleep

kill PID

kill -9 PID
```
## Part C: System Monitoring
### Commands Used
```bash
free -h
df -h
uptime
uname -a
```

## Part D: Service Monitoring
### Commands Used
```bash
systemctl status ssh

systemctl status NetworkManager
```
## Part E: Shell Scripting
### Script: system_report.sh
### Execute Script
```bash
chmod +x system_report.sh

./system_report.sh
```
## Part F: Security Monitoring Challenge
### netstat
* Purpose: Displays network connections.
### ss
* Purpose: Shows socket statistics.
### who
* Purpose: Shows logged-in users.
### w 
* Purpose: Shows user activity.
### last 
* Purpose: Shows login history.

## Tools Used
ps, top, htop, kill, free, df, uptime, uname, systemctl, who, w, last, netstat, ss, bash scripting.

## Conclusion
This task helped me understand Linux process management, system monitoring, services, and shell scripting basics.
