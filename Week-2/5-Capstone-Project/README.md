# Capstone Project - DVWA SQL Injection

## Objective:
Simulate a full penetration test by exploiting SQL Injection vulnerability in DVWA.

## Target:
http://127.0.0.1/DVWA

## Tool Used:
- sqlmap

## Vulnerability:
SQL Injection

## Command Used:
sqlmap -u "http://127.0.0.1/DVWA/vulnerabilities/sqli/?id=1&Submit=Submit" --cookie="PHPSESSID=YOUR_SESSION_ID; security=low" --dbs

## Exploitation Steps:
- Identified SQL injection point
- Extracted database names
- Enumerated tables
- Dumped user credentials

## Results:
- Database: dvwa
- Tables: users, guestbook, security_log, access_log
- Extracted user data successfully

## Status:
Successful exploitation

## Screenshots:
(Refer to screenshots folder)
