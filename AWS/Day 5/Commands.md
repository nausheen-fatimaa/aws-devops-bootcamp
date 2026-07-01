# AWS Day 5 Commands

## Apache Installation

```bash
sudo yum update -y
```

```bash
sudo yum install httpd -y
```

```bash
sudo systemctl enable httpd
```

```bash
sudo systemctl start httpd
```

---

## Check Apache Status

```bash
sudo systemctl status httpd
```

---

## Edit Website

```bash
sudo nano /var/www/html/index.html
```

---

## Restart Apache

```bash
sudo systemctl restart httpd
```

---

## Verify Website

Open:

http://13.233.250.215/
