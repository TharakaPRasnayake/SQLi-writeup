# TryHackMe Room: Mastering SQL Injection

## Overview

This room is designed to help learners understand and exploit various types of SQL Injection (SQLi) vulnerabilities in a controlled and educational environment. It covers four major types of SQLi attacks through practical demonstrations using a vulnerable web application.

---

## Objectives

- Understand and exploit **Classic Login Bypass**
- Identify and leverage **Error-Based SQLi**
- Perform **Union-Based SQLi** to extract data
- Use **Blind SQLi** techniques to extract information character-by-character
- Complete a **Final CTF Challenge** using all learned techniques

---

## Structure

### Task 1: Classic Login Bypass
- Bypass authentication by manipulating SQL queries in login forms.

### Task 2: Error-Based SQLi
- Trigger visible SQL errors to gain insights about the database.

### Task 3: Union-Based SQLi
- Use the `UNION` operator to combine results from different queries.

### Task 4: Blind SQLi
- Infer data by observing changes in the application's behavior.

### Task 5: Final CTF
- Apply all techniques to extract the final flag: `flag{SQLi_Master}`

---

## Prerequisites

- Basic knowledge of SQL
- Understanding of how web applications and databases interact
- Familiarity with tools like Burp Suite (optional)

---

## Deployment

This lab can be hosted on:
- Localhost (XAMPP/WAMP)
- InfinityFree (with limitations)
- Any PHP-enabled web server

Ensure the SQLi vulnerable site is properly configured before starting the room.

---

## Flag

Successfully completing the CTF will display the flag:
```
flag{SQLi_Master}
```

---

## License

This project is for **educational purposes only**. Do not use these techniques on real-world websites without proper authorization.
