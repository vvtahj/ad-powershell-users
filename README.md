<p align="center">
<img src="https://github.com/user-attachments/assets/67ea94d9-ef25-4bca-a182-6c5671746ccd" 
</p>

# ⚡ PowerShell: Bulk User Creation

## 📌 Overview
This lab explored how to automate user creation within Active Directory using PowerShell. I used a script to generate multiple users, assign them to an Organizational Unit, and confirm their creation by logging into the domain from a client machine.

## 🧰 Skills & Tools
- PowerShell Scripting  
- Active Directory Automation  
- Organizational Unit (OU) Management  
- Script Execution via PowerShell ISE  

## ✅ What Was Done
- Logged into the DC-1 virtual machine as `jane_admin`
- Opened PowerShell ISE with administrator privileges
- Downloaded and executed a PowerShell script to bulk-create users with unique usernames and passwords
- Verified user creation inside the `_EMPLOYEES` OU within Active Directory Users and Computers
- Successfully logged into Client-1 with one of the newly created accounts to confirm authentication

## 🛠️ Tools Used
- PowerShell ISE  
- AD Module for PowerShell  
- Active Directory Users and Computers (ADUC)  

## 🖼️ Screenshots  
*(Insert screenshots showing the script, PowerShell ISE, execution results, and user entries in ADUC)*

![Screenshot 2025-04-21 112826](https://github.com/user-attachments/assets/73075ee1-cb10-4197-8754-3b71f2ef0980)
![Screenshot 2025-04-21 112940](https://github.com/user-attachments/assets/2dc71580-4f9b-4823-a36b-fa677ce2822f)
![Screenshot 2025-04-21 112033](https://github.com/user-attachments/assets/ba187548-ca4b-45f6-a7dd-f6cf99a83025)


## 📘 Lessons Learned
- PowerShell scripting can greatly streamline repetitive administrative tasks  
- Automation ensures consistency and efficiency when creating multiple user accounts  
- Proper script testing and validation is critical before executing changes in production environments

