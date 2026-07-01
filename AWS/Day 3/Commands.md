# AWS Day 03 – Commands

## Update Ubuntu

sudo apt update
sudo apt upgrade -y

---

## Install Apache

sudo apt install apache2 -y

---

## Start Apache

sudo systemctl start apache2

---

## Enable Apache

sudo systemctl enable apache2

---

## Check Apache Status

sudo systemctl status apache2

---

## Edit Website

sudo nano /var/www/html/index.html

---

## Restart Apache

sudo systemctl restart apache2

---

## SSH Command

ssh -i day3-key.pem ubuntu@<Public-IP>

---

## Check Public IP

curl ifconfig.me

---

## Useful Linux Commands

pwd

ls

cd

cat

nano

mkdir

rm