**Logging Brute Force Attacks with Honeypots**

Project Overview

This project focuses on detecting and logging brute force attacks using honeypots, which are deceptive systems designed to attract attackers. By capturing malicious activities such as login attempts, IP addresses, and attack patterns, this project aims to strengthen cybersecurity measures and provide insights into attacker behavior. The collected logs are analyzed for better threat detection and mitigation.

**Tools Used :**

1. Hydra
            A powerful brute force tool for testing system vulnerabilities by attempting multiple username/password combinations.
2. Syslog-NG
             Logs and collects data for monitoring and analyzing system activities.
3. Nmap
            Performs network discovery and reconnaissance, enabling detection of open ports and services.
4. Juniper Router
           Configured for real-world simulation of brute force attempts.
5. Ubuntu OS
           A secure, open-source platform for hosting honeypots and running the testing environment.
6. V-Switch
           Enables network communication between virtualized environments and facilitates traffic flow for analysis.

**Features:**

Honeypots Deployment: Mimics vulnerable systems to attract attackers.
Activity Logging: Captures attack data such as IP addresses and login attempts.

Analysis: Uses logs to identify attack patterns and improve defense mechanisms.

Brute Force Simulation: Employs Hydra for controlled brute force testing.

Network Monitoring: Tracks incoming traffic using Syslog-NG and Nmap.

**Environment Setup:**

Configure Ubuntu OS with necessary tools.

Set up Syslog-NG for logging.

Deploy honeypots to simulate vulnerable systems.

_Brute Force Attack Simulation:_

Use Hydra to launch brute force attacks on honeypots.

Log attack data in Syslog-NG for analysis.

**Output Generation:**

Successful logging of attacks.

Detailed reports on attack patterns and IP sources.


**Outputs**

System Logs: Comprehensive logs of all brute force attempts, including timestamps, IP addresses, and attack details.

















