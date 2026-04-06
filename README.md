# 🔐 AI-Based Network Intrusion Detection System
AI-based Network Intrusion Detection System using MikroTik, Suricata, GNS3 and Python for automated threat detection, blocking and email alerts.

## 📌 Description
This project implements a hybrid **AI-based Network Intrusion Detection and Prevention System** using:

- MikroTik Router (Gateway & Firewall)
- Suricata (IDS/IPS)
- GNS3 (Network Simulation)
- Python (AI Automation)

The system is capable of detecting suspicious traffic, analyzing it using AI, automatically blocking malicious IPs, and sending real-time email alerts.

---

## ⚙️ Features
- 🔍 Real-time traffic monitoring
- 🚨 Intrusion detection using Suricata
- 🤖 AI-based traffic analysis
- 🔒 Automatic IP blocking on MikroTik
- 📧 Email alert notifications
- 🌐 Hybrid network (Physical + Virtual)

---

## 🧠 Architecture
Attacker → MikroTik → GNS3 → Suricata IDS/IPS
↓
Logs
↓
AI
↙ ↘
Block IP (MikroTik) Send Email Alert

---

## 🛠️ Technologies Used

- GNS3
- MikroTik RouterOS
- Suricata IDS/IPS
- Python (pandas, smtplib, paramiko)

---

## 🚀 How It Works

1. Attacker generates malicious traffic  
2. Suricata detects suspicious activity  
3. AI analyzes logs and identifies attacker IP  
4. System automatically blocks the IP via MikroTik  
5. Email alert is sent to the administrator  



## 📂 Project Structure
ai-network-intrusion-detection/
│
├── README.md
├── ai/
├── mikrotik/
├── suricata/
├── gns3/
└── docs/


---

## 👨‍💻 Author
Rigers Maja
