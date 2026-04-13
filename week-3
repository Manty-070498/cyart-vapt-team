# Week 03 - Full VAPT Cycle (Capstone Project)

## 📌 Objective

The objective of this project is to perform a full Vulnerability Assessment and Penetration Testing (VAPT) cycle on a vulnerable system using Kali Linux tools. The project follows the PTES (Penetration Testing Execution Standard) methodology, including reconnaissance, scanning, exploitation, post-exploitation, and reporting.

---

## 🛠️ Tools Used

* Kali Linux
* Metasploit Framework
* Nikto (used as alternative to OpenVAS)

---

## 🧪 Methodology (PTES)

### 1. Reconnaissance

* Identified target machine IP: **192.168.56.101**
* Observed running services

### 2. Vulnerability Scanning

* Used **Nikto** to scan the web server
* Identified:

  * Outdated Apache version (2.2.8)
  * Missing security headers
  * HTTP TRACE method enabled
  * Directory enumeration vulnerability

### 3. Exploitation

* Used **Metasploit Framework**
* Exploited **Samba usermap_script vulnerability**
* Successfully gained shell access
* Verified root access using:

  ```
  whoami → root
  ```

### 4. Post-Exploitation

* Verified system access
* Collected basic system information

### 5. Reporting

* Documented vulnerabilities
* Provided remediation recommendations

---

## ⚠️ OpenVAS Limitation

OpenVAS (GVM) was initially intended for vulnerability scanning. However, it could not be used due to configuration issues, including feed synchronization failures and service errors. Therefore, **Nikto** was used as an alternative scanning tool to complete the assessment.

---

## 📊 Key Findings

* Outdated Apache server (EOL)
* Missing HTTP security headers
* HTTP TRACE enabled (XST vulnerability)
* Directory enumeration possible

---

## 🛡️ Remediation

* Update Apache to latest version
* Disable HTTP TRACE method
* Implement security headers
* Restrict directory listing
* Apply regular security patches

---

## ✅ Result

✔ Vulnerabilities successfully identified
✔ Target system exploited
✔ Root-level access obtained

---

## 📂 Repository Structure

* Documentation (PDF report, notes, screenshots)
* Workflow (step-by-step process)
* README (project overview)

---

## 📝 Note

This project demonstrates a complete VAPT cycle in a controlled lab environment for educational purposes only.
