# VAPT Workflow Steps

## 1. Reconnaissance

* Identified target IP (192.168.56.101)

## 2. Scanning

* Used Nikto for vulnerability scanning
* Discovered outdated Apache version and missing headers

## 3. Exploitation

* Used Metasploit Framework
* Exploited Samba vulnerability (usermap_script)
* Gained root shell access

## 4. Post-Exploitation

* Verified root access using "whoami"
* Retrieved system information

## 5. Reporting

* Documented vulnerabilities
* Provided remediation recommendations
