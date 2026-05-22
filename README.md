# Network-Reconnaissance
Performed network scanning and service enumeration using the Metasploit Framework to identify active hosts and open ports.

## Cybersecurity Project Report
- Project Type:	Personal Cybersecurity Practice Lab
- Domain	Ethical Hacking / Network Scanning
- Tool Used	Metasploit Framework
- Prepared By	A Abhishek
- Date	25/04/26

### Overview
This project was performed as a personal cybersecurity practice lab to understand how network scanning is performed using the Metasploit Framework. The main objective of this lab was to identify live hosts, open ports, and running services in a target network environment using Metasploit scanning modules. This project helped in understanding how ethical hackers gather network-related information during the reconnaissance and scanning phases of penetration testing.

### Contents
1.	Introduction
2.	Objectives
3.	Tools Used
4.	Methodology
5.	Network Scanning using Metasploit
6.	Observations
7.	Challenges Faced
8.	Conclusion

### Introduction
Network scanning is one of the important phases in ethical hacking and penetration testing. It helps security professionals discover active systems, open ports, running services, and vulnerabilities within a target network. Scanning tools are commonly used to collect information about devices connected to the network. The collected information helps in identifying potential security weaknesses and understanding the target environment. In this lab, the Metasploit Framework was used to perform network scanning operations on a target network. Metasploit provides multiple auxiliary modules that can be used for scanning and information gathering.

### Objectives
The objectives of this project are:
-	To understand the basics of network scanning
-	To learn how Metasploit is used during reconnaissance
-	To identify live hosts in a target network
-	To scan open ports and running services
-	To understand how scanning helps ethical hackers during penetration testing
-	To gain practical experience using Metasploit auxiliary modules

 ### Tools Used
-	Parrot Security (Linux)
-	Metasploit Framework
-	Linux Terminal
-	Target IP Address / Target Network
-	Internet or Local Lab Network

 ### Methodology
The following steps were performed during this project:
1.	Opened the Parrot Security Linux terminal.
2.	Started the Metasploit Framework.
3.	Selected the required auxiliary scanning module.
4.	Configured the target IP address or network range.
5.	Executed the scan.
6.	Analyzed the discovered hosts, ports, and services.
7.	Documented the results obtained during scanning.

 ### Network Scanning using Metasploit
#### Step 1: Launch Metasploit Framework
The Metasploit Framework was started using the following command:
>	"msfconsole"
This launched the Metasploit environment used for scanning and reconnaissance.

<img width="975" height="731" alt="image" src="https://github.com/user-attachments/assets/4bd58b5f-1f44-4d6a-93f0-393f8a4ec1fa" />

#### Step 2: Search for Scanning Modules
The available scanning modules were searched using the following command:
>	"search portscan"
This displayed multiple auxiliary modules related to network scanning.

#### Step 3: Select a Scanner Module
A suitable scanner module was selected for scanning the target network.
>	"use auxiliary/scanner/portscan/syn"

#### Step 4: Configure Target IP Address
The target IP address was configured using the following command:
>	"set RHOSTS 10.10.1.22"

<img width="975" height="731" alt="image" src="https://github.com/user-attachments/assets/a8c358c2-2364-496b-8f90-9878d2c9d55b" />

#### Step 5: Run the Scan
The scan was executed using:
>	"run"
Metasploit scanned the target system and displayed information about open ports and services.
>
<img width="975" height="731" alt="image" src="https://github.com/user-attachments/assets/e1f90922-1e19-4367-b048-3757deb7433c" />

#### Step 6: Analyze the Results
The scan results displayed:
-	Open TCP ports
-	Active hosts
-	Running services
-	Service banners (in some cases)

The information gathered during scanning can help security professionals understand the target network structure.

<img width="975" height="731" alt="image" src="https://github.com/user-attachments/assets/c5af2e5d-dc17-49ad-af21-ccf6cb3f6c05" />

### Observations
During the scanning process, the following observations were made:
-	Metasploit successfully identified active hosts in the network.
-	Open ports were detected on the target system.
-	Some services were identified through port scanning.
-	The scanning process helped in understanding the network exposure of the target system.
-	Different scanner modules can be used depending on the required information.

The lab demonstrated how network scanning tools assist ethical hackers in gathering technical information about a target environment.

### Challenges Faced
Some challenges encountered during the lab were:
-	Incorrect target IP configuration initially
-	Slow scanning speed due to network latency
-	Some ports were filtered by firewall rules
-	Understanding the functionality of different Metasploit modules required additional practice

These issues were resolved by verifying configurations and selecting appropriate scanning modules.

### Conclusion
This project provided practical exposure to network scanning using the Metasploit Framework. The lab demonstrated how ethical hackers gather information about target systems such as open ports, live hosts, and running services. By using Metasploit auxiliary scanner modules, the target network was successfully analyzed. This project improved understanding of reconnaissance and scanning techniques used during penetration testing and cybersecurity assessments. The knowledge gained from this lab can be useful for future learning in ethical hacking, vulnerability assessment, and network security testing
