cybersecurity-internshipAdd commentMore actions

# Cybersecurity Internship – Task 4  
## Firewall Configuration and Traffic Filtering

---

###  Task Overview

This project is part of the cybersecurity internship where the objective is to configure a basic firewall on Kali Linux using `ufw`, block insecure services like **Telnet**, and allow secure services like **SSH**. The task also includes verifying that the firewall is filtering traffic correctly.

---

##  Firewall Configuration Details

- **Firewall Tool Used**: UFW (Uncomplicated Firewall)
- **Ports Configured**:
  -  Port **23** (Telnet): **Blocked**
  -  Port **22** (SSH): **Allowed**
- **Firewall Status**: Active and Logging Enabled

---![firewall1](https://github.com/user-attachments/assets/2618546f-d60a-4b5b-bcfd-fe664539ae60)


###  Commands Used 


bash commanda:

sudo apt install ufw -y
sudo ufw enable
sudo ufw deny 23
sudo ufw allow 22
sudo ufw status numbered
sudo ufw status verbose

sudo systemctl start ssh
telnet 127.0.0.1 22

Connected to 127.0.0.1
SSH-2.0-OpenSSH_10.0p2 Debian-5

telnet 127.0.0.1 23
telnet: Unable to connect to remote host: Connection refused

![firewall2](https://github.com/user-attachments/assets/1599c0eb-9c45-4755-aaa5-2884ad98a632)
