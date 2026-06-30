# Linux Day 3 - Commands Practiced

## Process Management

```bash
ps
```

Displays running processes for the current terminal.

```bash
ps -ef
```

Displays all running processes in full format.

```bash
ps aux
```

Displays all running processes with CPU and memory usage.

```bash
top
```

Displays live system processes and resource utilization.

```bash
htop
```

Interactive process monitoring tool.

```bash
pgrep bash
```

Finds the Process ID (PID) of bash.

```bash
pidof bash
```

Displays the PID of a running bash process.

```bash
sleep 300 &
```

Runs a process in the background.

```bash
jobs
```

Displays background jobs.

```bash
kill <PID>
```

Terminates a running process.

---

## Service Management

```bash
systemctl list-units --type=service
```

Lists all active services.

```bash
systemctl status apache2
```

Checks Apache service status.

```bash
sudo systemctl start apache2
```

Starts Apache.

```bash
sudo systemctl stop apache2
```

Stops Apache.

```bash
sudo systemctl restart apache2
```

Restarts Apache.

```bash
sudo systemctl enable apache2
```

Starts Apache automatically after boot.

```bash
sudo systemctl disable apache2
```

Disables Apache auto-start.

---

## Package Management

```bash
sudo apt update
```

Updates package information.

```bash
sudo apt upgrade -y
```

Upgrades installed packages.

```bash
apt search nginx
```

Searches for the nginx package.

```bash
sudo apt install nginx -y
```

Installs nginx.

```bash
sudo apt remove nginx -y
```

Removes nginx.

```bash
sudo apt autoremove -y
```

Removes unused packages.

---

## Log Management

```bash
cd /var/log
```

Navigates to log directory.

```bash
ls
```

Lists available log files.

```bash
sudo less syslog
```

Views system logs.

```bash
sudo less auth.log
```

Views authentication logs.

```bash
grep ssh auth.log
```

Searches SSH entries.

```bash
tail -20 syslog
```

Displays last 20 log entries.

```bash
tail -f syslog
```

Monitors logs in real time.

---

## Cron Jobs

```bash
crontab -l
```

Lists cron jobs.

```bash
crontab -e
```

Edits cron jobs.
