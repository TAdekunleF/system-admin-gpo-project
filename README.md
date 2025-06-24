# Windows Server Lab: Active Directory, PowerShell Automation & Group Policy

This hands-on lab simulates a fully functional Windows Server environment built from scratch. It covers the complete deployment of Active Directory, structured Organizational Units (OUs), automated user onboarding with PowerShell, and Group Policy Object (GPO) configurations for software installation, security enforcement, and desktop customization.

Designed to demonstrate real-world IT infrastructure setup and endpoint management skills.

---

## 🔧 Lab Objectives

- Configure a Windows Server Domain Controller with `Active Directory Domain Services (AD DS)`
- Create Organizational Units (HR, IT, etc.) to logically group users
- Automate user creation using PowerShell
- Apply Group Policy Objects (GPOs) to:
  - Enforce password policies
  - Install software (e.g., Google Chrome) at logon
  - Deploy desktop wallpaper across departments

---

## 🧪 Key Features

- **OU Structure** with HR and IT groups
- **PowerShell Scripting** for batch user onboarding
- **GPO Deployment**:
  - Password policy (min length, complexity, aging)
  - Software installation via MSI
  - Wallpaper configuration via network share

---

## 🖼️ Screenshots

### OU and User Creation

![OU Creation](images/ou-creation-powershell.png)
![User Creation](images/user-creation-powershell.png)

### GPO Linked to HR OU

![GPO Linked to HR](images/GPO-linked-to-HR.png)

### Software Deployment via GPO

![Software Deployment](images/GPO-Configuration.png)

### Password Policy Enforcement

![Password Policy](images/Security-Setting-Enforce.png)

---

## 📁 Project Structure

