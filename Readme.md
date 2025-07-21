# Managing Users, Groups, and File Permissions in Linux  
**Cybersecurity Portfolio Project**

## 📌 Overview

This project demonstrates my ability to manage users, groups, directories, and permissions in a Linux environment using essential administrative commands.

It was completed as part of my cybersecurity learning journey, aligned with topics covered in the Google Cybersecurity Certificate.

---

## 🛠️ Skills Demonstrated

- Creating users with `useradd` and setting passwords
- Creating groups and adding users to them using `groupadd` and `usermod`
- Assigning directory ownership using `chown`
- Setting secure file and directory permissions using `chmod`
- Verifying configurations with `groups` and `ls -ld`

---

## 🧪 Commands Used

```bash
# Create user and set password
sudo useradd researcher2
sudo passwd researcher2

# Create group and add user to it
sudo groupadd cyber_team
sudo usermod -aG cyber_team researcher2
groups researcher2

# Create project directory and assign ownership
sudo mkdir /home/cyber_lab
sudo chown researcher2:cyber_team /home/cyber_lab
ls -ld /home/cyber_lab

# Set directory permissions
sudo chmod 770 /home/cyber_lab
ls -ld /home/cyber_lab
