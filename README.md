# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-69-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--12-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-25.18%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 24 of 61
- **Practitioner**: 43 of 174
- **Expert**: 2 of 39

## Categories Covered

- **Authentication vulnerabilities**: 14/14 lab
- **SQL injection**: 18/18 lab
- **Path traversal**: 6/6 lab
- **Command injection**: 5/5 lab
- **Access control**: 13/13 lab
- **Information disclosure**: 5/5 lab
- **Business logic vulnerabilities**: 8/13 lab

## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite
- Some PortSwigger labs appear in more than one topic (for example, **2FA simple bypass**, **2FA broken logic**, and **Password reset broken logic**). These labs are recorded only once in this tracker to avoid duplicate entries and to keep the total lab count accurate.

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date | Topic | Lab Title | Difficulty | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1 | 2026-06-15 | SQL Injection | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | Apprentice | N/A |
| 2 | 2026-06-15 | SQL Injection | SQL injection vulnerability allowing login bypass | Apprentice | N/A |
| 3 | 2026-06-16 | SQL Injection | SQL injection UNION attack, determining the number of columns returned by the query | Practitioner | N/A |
| 4 | 2026-06-16 | SQL Injection | SQL injection UNION attack, finding a column containing text | Practitioner | N/A |
| 5 | 2026-06-17 | SQL Injection | SQL injection UNION attack, retrieving data from other tables | Practitioner | N/A |
| 6 | 2026-06-17 | SQL Injection | SQL injection UNION attack, retrieving multiple values in a single column | Practitioner | N/A |
| 7 | 2026-06-18 | SQL Injection | Blind SQL injection with conditional responses | Practitioner | N/A |
| 8 | 2026-06-18 | SQL Injection | Blind SQL injection with conditional errors | Practitioner | N/A |
| 9 | 2026-06-19 | SQL Injection | Visible error-based SQL injection | Practitioner | N/A |
| 10 | 2026-06-19 | SQL Injection | Blind SQL injection with time delays | Practitioner | N/A |
| 11 | 2026-06-19 | SQL Injection | Blind SQL injection with time delays and information retrieval | Practitioner | N/A |
| 12 | 2026-06-21 | SQL Injection | SQL injection with filter bypass via XML encoding | Practitioner | N/A |
| 13 | 2026-06-21 | SQL Injection | SQL injection attack, querying the database type and version on Oracle | Practitioner | N/A |
| 14 | 2026-06-21 | SQL Injection | SQL injection attack, querying the database type and version on MySQL and Microsoft | Practitioner | N/A |
| 15 | 2026-06-21 | SQL Injection | SQL injection attack, listing the database contents on non-Oracle databases | Practitioner | N/A |
| 16 | 2026-06-21 | SQL Injection | SQL injection attack, listing the database contents on Oracle | Practitioner | N/A |
| 17 | 2026-06-21 | SQL Injection | Blind SQL injection with out-of-band interaction | Practitioner | N/A |
| 18 | 2026-06-23 | Authentication | Username enumeration via different responses | Apprentice | N/A |
| 19 | 2026-06-23 | Authentication | Username enumeration via subtly different responses | Practitioner | N/A |
| 20 | 2026-06-24 | Authentication | 2FA simple bypass | Apprentice | N/A |
| 21 | 2026-06-24 | Authentication | 2FA broken logic | Practitioner | N/A |
| 22 | 2026-06-24 | Authentication | Brute-forcing a stay-logged-in cookie | Practitioner | N/A |
| 23 | 2026-06-26 | Authentication | Offline password cracking | Practitioner | N/A |
| 24 | 2026-06-26 | Authentication | Password reset broken logic | Apprentice | N/A |
| 25 | 2026-06-26 | Authentication | Password reset poisoning via middleware | Practitioner | N/A |
| 26 | 2026-06-26 | Authentication | Password brute-force via password change | Practitioner | N/A |
| 27 | 2026-06-26 | Authentication | Username enumeration via account lock | Practitioner | N/A |
| 28 | 2026-06-26 | Authentication | Username enumeration via response timing | Practitioner | N/A |
| 29 | 2026-06-26 | Authentication | Broken brute-force protection, IP block | Practitioner | N/A |
| 30 | 2026-06-27 | Authentication | Broken brute-force protection, multiple credentials per request | Expert | N/A |
| 31 | 2026-06-28 | Authentication | 2FA bypass using a brute-force attack | Expert | N/A |
| 32 | 2026-06-30 | Path Traversal | File path traversal, traversal sequences blocked with absolute path bypass | Practitioner | N/A |
| 33 | 2026-06-30 | Path Traversal | File path traversal, simple case | Apprentice | N/A |
| 34 | 2026-07-01 | Path Traversal | File path traversal, traversal sequences stripped non-recursively | Practitioner | N/A |
| 35 | 2026-07-01 | Path Traversal | File path traversal, traversal sequences stripped with superfluous URL-decode | Practitioner | N/A |
| 36 | 2026-07-01 | Path Traversal | File path traversal, validation of start of path | Practitioner | N/A |
| 37 | 2026-07-01 | Path Traversal | File path traversal, validation of file extension with null byte bypass | Practitioner | N/A |
| 38 | 2026-07-02 | Command Injection | OS command injection, simple case | Apprentice | N/A |
| 39 | 2026-07-02 | Command Injection | Blind OS command injection with time delays | Practitioner | N/A |
| 40 | 2026-07-02 | Command Injection | Blind OS command injection with output redirection | Practitioner | N/A |
| 41 | 2026-07-03 | Command Injection | Blind OS command injection with out-of-band interaction | Practitioner | N/A |
| 42 | 2026-07-03 | Command Injection | Blind OS command injection with out-of-band data exfiltration | Practitioner | N/A |
| 43 | 2026-07-03 | SQL Injection | Blind SQL injection with out-of-band data exfiltration | Practitioner | N/A |
| 44 | 2026-07-04 | Access Control | Unprotected admin functionality | Apprentice | N/A |
| 45 | 2026-07-04 | Access Control | Unprotected admin functionality with unpredictable URL | Apprentice | N/A |
| 46 | 2026-07-04 | Access Control | User role controlled by request parameter | Apprentice | N/A |
| 47 | 2026-07-04 | Access Control | User role can be modified in user profile | Apprentice | N/A |
| 48 | 2026-07-04 | Access Control | URL-based access control can be circumvented | Practitioner | N/A |
| 49 | 2026-07-04 | Access Control | Method-based access control can be circumvented | Practitioner | N/A |
| 50 | 2026-07-07 | Access Control | User ID controlled by request parameter | Apprentice | N/A |
| 51 | 2026-07-07 | Access Control | User ID controlled by request parameter, with unpredictable user IDs | Apprentice | N/A |
| 52 | 2026-07-07 | Access Control | User ID controlled by request parameter with data leakage in redirect | Apprentice | N/A |
| 53 | 2026-07-07 | Access Control | User ID controlled by request parameter with password disclosure | Apprentice | N/A |
| 54 | 2026-07-07 | Access Control | Insecure direct object references | Apprentice | N/A |
| 55 | 2026-07-07 | Access Control | Multi-step process with no access control on one step | Practitioner | N/A |
| 56 | 2026-07-07 | Access Control | Referer-based access control | Practitioner | N/A |
| 57 | 2026-07-08 | Information Disclosure | Information disclosure in error messages | Apprentice | N/A |
| 58 | 2026-07-08 | Information Disclosure | Information disclosure on debug page | Apprentice | N/A |
| 59 | 2026-07-10 | Business Logic Vulnerabilities | Excessive trust in client-side controls | Apprentice | N/A |
| 60 | 2026-07-10 | Business Logic Vulnerabilities | High-level logic vulnerability | Apprentice | N/A |
| 61 | 2026-07-10 | Information Disclosure | Source code disclosure via backup files | Apprentice | N/A |
| 62 | 2026-07-10 | Information Disclosure | Authentication bypass via information disclosure | Apprentice | N/A |
| 63 | 2026-07-11 | Information Disclosure | Information disclosure in version control history | Practitioner | N/A |
| 64 | 2026-07-11 | Business Logic Vulnerabilities | Inconsistent handling of exceptional input | Practitioner | N/A |
| 65 | 2026-07-11 | Business Logic Vulnerabilities | Inconsistent security controls | Apprentice | N/A |
| 66 | 2026-07-11 | Business Logic Vulnerabilities | Weak isolation on dual-use endpoint | Practitioner | N/A |
| 67 | 2026-07-11 | Business Logic Vulnerabilities | Insufficient workflow validation | Practitioner | N/A |
| 68 | 2026-07-12 | Business Logic Vulnerabilities | Flawed enforcement of business rules | Apprentice | N/A |
| 69 | 2026-07-12 | Business Logic Vulnerabilities | Infinite money logic flaw | Practitioner | N/A |
