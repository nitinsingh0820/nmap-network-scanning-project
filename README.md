**Network Scanning using Nmap**

Internship Project

Domain: Cybersecurity \& Ethical Hacking

Organization: SkillInfyTech



**Objective**

The objective of this project is to perform basic network scanning and identify open ports and services using Nmap.



**Introduction**

Nmap (Network Mapper) is an open-source cybersecurity tool used for:

\* Network discovery

\* Port scanning

\* Service detection

\* Security auditing

It helps cybersecurity professionals understand network communication and identify active services running on systems.



**System Requirements**

\* Windows Operating System

\* Nmap Tool

\* Internet Connection

\* Command Prompt



**Installation Process**

**Step 1: Download Nmap**

Nmap was downloaded from the official website: https://nmap.org/download.html



**Step 2: Install Nmap**

The Windows installer was executed and default installation settings were used.



**Step 3: Open Command Prompt**

Command Prompt was opened using:

Windows + R



Then:

cmd



**Project Execution**

**1. Localhost Scan**



**Command Used**

nmap localhost



**Purpose**

This command scans the local machine (127.0.0.1) and identifies open ports and running services.



**Output Obtained**

The scan identified the following open ports:

Port       135/tcp        445/tcp

State      Open           Open

Service    msrpc          microsoft-ds





**Analysis**

\* Port 135 is used for Microsoft Remote Procedure Call (MSRPC).

\* Port 445 is used for SMB (Server Message Block) file sharing services.

\* These services are commonly found on Windows systems.







**2. Public Test Server Scan**



**Command Used**

nmap scanme.nmap.org



**Purpose**

This command scans the official Nmap public testing server to identify open and filtered ports.



**Output Obtained**

The scan identified several ports and services.



Port        22/tcp       80/tcp      9929/tcp       31337/tcp     25/tcp

State       Open         Open        Open           Open          Filtered

Service     ssh          http        nping-echo     Elite         smtp





**Analysis**

\* Port 22 is used for secure remote login through SSH.

\* Port 80 is used for HTTP web services.

\* Filtered ports indicate firewall or security filtering.

\* The scan demonstrates how Nmap detects services running on remote systems.









**Screenshots**

**Localhost Scan**
![alt text](localhost-scan-1.png)


**Public Test Server Scan**
![alt text](scanme-scan-1.png)

**Learning Outcomes**

Through this project, the following concepts were learned:

\* Basic network scanning

\* Open port identification

\* Service detection

\* Localhost scanning

\* Remote host scanning

\* Importance of cybersecurity and network monitoring



**Challenges Faced**

While attempting local network scanning, some network restrictions prevented ARP scanning on the network. Therefore, localhost and official Nmap test server scans were performed successfully.



**Conclusion**

This project provided practical experience with the Nmap tool and basic cybersecurity techniques. The project demonstrated how open ports and running services can be identified using network scanning methods.



**Submitted By**

Name: Nitin Kumar Singh

Internship Domain: Cybersecurity \& Ethical Hacking

Organization: SkillInfyTech

