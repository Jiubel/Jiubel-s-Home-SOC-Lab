# 🛡️ Home SOC Lab (Wazuh + Cowrie Honeypot)

## 📌 Objective
This project focuses on building a home SOC lab to simulate attacker activity and observe how it is captured, ingested, and analyzed within a SIEM. It highlights the end-to-end process of detection and basic security event investigation.

## 🧱 Tools Used
- Wazuh (SIEM / Log Analysis)
- Cowrie (SSH Honeypot)
- VirtualBox (Lab Environment)
- Linux (Ubuntu)

## 🏗️ Lab Setup
The lab was built using Oracle VM VirtualBox with multiple virtual machines to simulate a basic SOC environment. Wazuh was configured as the central SIEM for log collection and analysis, while Cowrie was deployed as an SSH honeypot to capture and monitor attacker activity.

## 🎯 What I Did

- Set up a virtual SOC lab using Oracle VM VirtualBox  
- Installed and configured Wazuh for log monitoring and alerting  
- Simulated failed login attempts to generate authentication logs  
- Verified detection of suspicious activity in Wazuh  
- Deployed Cowrie honeypot to capture attacker interactions  
- Simulated attacker access via SSH and executed commands  
- Analyzed honeypot activity and alerts within the Wazuh dashboard  
