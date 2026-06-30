# Linux Day 05 - Commands Documentation

## Linux Networking Commands

### Display IP Address

```bash
ip addr
```

Displays all network interfaces and their assigned IP addresses.

---

### Display Routing Table

```bash
ip route
```

Shows routing information including the default gateway.

---

### Display Current IP

```bash
hostname -I
```

Shows the IP address assigned to the system.

---

### Test Internet Connectivity

```bash
ping google.com
```

Checks whether the system can communicate with another host.

---

### Retrieve Webpage

```bash
curl https://example.com
```

Downloads webpage content and displays it in the terminal.

---

### Download Files

```bash
wget https://example.com
```

Downloads files from the internet.

---

### Show Listening Ports

```bash
ss -tuln
```

Displays active TCP and UDP listening ports.

---

### Show Active Connections

```bash
netstat -tuln
```

Displays network connections and listening ports.

---

### DNS Lookup

```bash
nslookup google.com
```

Converts a domain name into an IP address.

---

## AWS Commands

### Update Package List

```bash
sudo apt update
```

Updates repository information.

---

### Upgrade Packages

```bash
sudo apt upgrade -y
```

Installs the latest package updates.

---

### Install Apache

```bash
sudo apt install apache2 -y
```

Installs Apache Web Server.

---

### Check Apache Status

```bash
sudo systemctl status apache2
```

Displays Apache service status.

---

### Start Apache

```bash
sudo systemctl start apache2
```

Starts the Apache service.

---

### Enable Apache

```bash
sudo systemctl enable apache2
```

Configures Apache to start automatically after reboot.

---

### Navigate to Web Directory

```bash
cd /var/www/html
```

Moves to the Apache web root directory.

---

### Edit Homepage

```bash
sudo nano index.html
```

Edits the default Apache webpage.