![LINUX Logo](./linux.webp)

# ⭐ Linux DevOps Automation Suite

A collection of automation scripts designed for real-world DevOps and DevSecOps scenarios.  
This project demonstrates log analysis, system administration, backup automation, user provisioning, string manipulation, and configuration updates across multiple Linux-based workflows.

Each part represents a real industry use case and can be showcased in DevOps interviews or added to a professional portfolio.

---

## 🚀 Technologies & Tools

- **Linux / Bash Scripting**
- **sed / awk / grep / cut / uniq**
- **Cronjob Scheduling**
- **CloudTrail Log Analysis**
- **JSON Manipulation**
- **Terraform Config Editing**
- **Security Log Auditing**
- **User & Password Management**

---

## 📁 Project Structure

```
Linux_DevOps_Automation_Suite/
│
├── docs/
│ └── Project_README.md
│
├── First_Part/ # Security Issue Investigation
│ ├── event_history.csv
│ ├── result.txt
│ └── script.sh
│
├── Second_Part/ # User & Password Automation
│ └── user_passwd.sh
│
├── Third_Part/ # Backup Automation & Cronjob
│ └── backup.sh
│
├── Fourth_Part/
│ ├── Task_1/
│ │ ├── info.json
│ │ ├── terraform.tf
│ │ └── command.sh
│ │
│ ├── Task_2/
│ │ ├── certificate.pem
│ │ └── new.pem
│ │
│ └── Task_3/
│ ├── auth.logs
│ └── invalid_user.sh
│
└── README.md
```

```md
📚 **Detailed Scenario Documentation:**  
See full task descriptions here:  
➡️ [docs/Project_README.md](docs/Project_README.md)

---

# 🧩 Part 1 – Security Issue Investigation

A financial company suspects that an internal user named **Paul** terminated a critical EC2 instance.  
Using CloudTrail logs, the automation script:

- Filters all termination events
- Extracts only instance IDs terminated by **Paul**
- Saves results into `result.txt`

### Skills demonstrated

✔ Log analysis  
✔ Pattern matching  
✔ Linux command-line automation

---

# 👥 Part 2 – User Provisioning Automation

This script automates user creation across multiple Linux systems:

- Creates a new Linux account
- Generates a secure random password
- Enforces password reset on first login
- Verifies successful account creation

This removes repetitive workload from system administrators and enables HR to create accounts independently.

---

# 📦 Part 3 – Backup Automation + Cronjob

A gaming company stores rapidly changing game data inside `/home/ec2-user/data`.  
Critical system directories such as `/etc`, `/boot`, and `/usr` must also be backed up.

The backup script:

- Compresses selected directories into `.tgz`
- Uses hostname + timestamp for naming
- Stores files inside `/mnt/backup`
- Runs automatically every **5 minutes** via cronjob

### Skills demonstrated

✔ Backup strategy design  
✔ Disaster recovery automation  
✔ Cron scheduling  
✔ Timestamped file management

---

# 🧵 Part 4 – String Manipulation Tasks

## 🔹 Task 1 – JSON → Terraform Auto-Update

Extracts the EC2 private IP from `info.json` and updates it inside `terraform.tf` **without manual editing**.

### Skills

- JSON extraction
- sed inline replacement
- Automated config updates

---

## 🔹 Task 2 – Convert Single-Line PEM → Multi-Line PEM

Reformats `certificate.pem` from a single-line blob into a correctly formatted PEM (`new.pem`).

### Skills

- Text reconstruction
- Data normalization
- Secure formatting techniques

---

## 🔹 Task 3 – SSH Invalid User Detection

Parses `auth.logs` to identify invalid SSH login attempts.

The script:

- Extracts invalid usernames
- Counts login attempts per username
- Outputs a clean summary report

### Skills

- Security auditing
- Intrusion attempt detection
- Log analytics

---

# 🎯 Learning Outcomes

By completing this project you'll gain hands-on experience with:

- Advanced Bash scripting & Linux automation
- Log parsing and security monitoring
- Cron-based scheduling & backup strategies
- JSON / PEM manipulation
- Infrastructure-as-Code preparation
- System administration automation
- Real DevOps/DevSecOps workflows

---

# 🤝 Contributions

This repository is made for education and portfolio building.  
Pull requests, feature suggestions, and improvements are welcome.
```
