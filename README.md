#  Packet Analysis & MITM Attacks Using Open-Source Tools


##  Executive Summary
This project demonstrates **packet analysis and Man-in-the-Middle (MITM) attack simulation** in a controlled lab environment using open-source tools.

The objective is to analyze network traffic, understand protocol behavior, and demonstrate how attackers can intercept sensitive data in unsecured networks.



##  Objectives
- Capture and analyze live network traffic  
- Understand TCP/IP protocols (HTTP, DNS, ICMP)  
- Perform packet filtering and inspection  
- Simulate MITM attacks using ARP spoofing  
- Demonstrate risks of unencrypted communication  



##  Tools Used
- **Tcpdump** – Packet capture  
- **Tshark** – Protocol analysis  
- **Ettercap** – MITM attack simulation  
- **Bettercap** – Advanced network monitoring  



##   Project Structure

```
packet-analysis-mitm-attacks/
│
├── README.md
├── commands.txt
└── project-report.pdf
```

##  Methodology

### 1. Reconnaissance
- Captured live packets using Tcpdump  
- Observed normal network traffic  

### 2. Packet Analysis
- Used Tshark for protocol inspection  
- Filtered HTTP, DNS, and ICMP traffic  

### 3. MITM Attack
- Performed ARP spoofing  
- Intercepted communication between victim and gateway  

### 4. Data Analysis
- Extracted sensitive information from captured traffic  
- Verified successful interception  



##  Key Findings

###  Unencrypted Traffic (High)
- HTTP traffic is transmitted in plain text  
- Credentials can be intercepted بسهولة  

###  ARP Spoofing (High)
- Successfully redirected traffic through attacker  
- Enabled full traffic monitoring  

###   Lack of Network Protection (Medium)
- No detection mechanisms for MITM attacks  


 

##  Results
- Successfully captured network packets  
- Performed MITM attack using ARP spoofing  
- Intercepted HTTP credentials  
- Analyzed traffic using CLI tools  




##   Security Implications
- Use **HTTPS (TLS encryption)**  
- Avoid unsecured networks  
- Monitor network traffic  
- Implement ARP spoofing protection  




##   Conclusion
This project proves that **unencrypted communication is highly vulnerable** and can be easily exploited using MITM attacks.

It highlights the importance of:
- Encryption (HTTPS)  
- Network security controls  
- Awareness of attack techniques  




##  Author

**Ayisha Minha**  
Cybersecurity Student
