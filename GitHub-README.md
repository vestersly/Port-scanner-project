# Python Port Scanner Project

## 🚀 Project Overview

This project demonstrates a simple yet powerful **TCP Port Scanner** built using **Python's socket module**. 
It allows scanning of a target IP address within a specified port range to detect open ports and evaluate their associated risks.

The scanner was developed and tested as part of a cybersecurity learning journey and includes documentation, risk analysis, and a presentation suitable for a jury or technical review panel.

---

## 🛠️ Tools & Technologies Used

- Python 3
- socket (built-in Python networking module)
- Command-line interface (CLI)
- `netstat -ab` for verifying open ports on Windows
- Microsoft PowerPoint for reporting

---

## 📂 Folder Structure

```
port_scanner_project/
├── src/
│   ├── portscan.py               # Main scanner with test capability
│   └── risky_port_check.py       # Script to scan for dangerous ports
│
├── reports/
│   ├── Final_Port_Scanner_Project_Report.docx
│
├── presentation/
│   └── Port_Scanner_Project_Presentation.pptx
│
├── screenshots/                  # Screenshots of terminal and test output (optional)
│   └── scan_example.png
```

---

## 📊 Example Scan Output

```
Scanning 127.0.0.1 from port 20 to 100
Port 13 is OPEN
Port 17 is OPEN
Port 19 is OPEN
Port 80 is OPEN
Port 135 is OPEN
Port 445 is OPEN
```

---

## 🔐 Risk Analysis

| Port | Service    | Risk Description |
|------|------------|------------------|
| 13   | Daytime    | DDoS reflection, legacy service |
| 17   | QOTD       | DDoS reflection |
| 19   | Chargen    | DDoS amplification |
| 135  | MS RPC     | RPC DCOM exploit, lateral movement |
| 445  | SMB        | Known SMB vulnerabilities (e.g., WannaCry) |

---

## 📄 Reports & Documentation

- **Final_Port_Scanner_Project_Report.docx**: Combines software design, testing, ethical considerations, and detection techniques
- **Port_Scanner_Project_Presentation.pptx**: 8-slide professional slide deck for presenting the project

---

## 🤝 About the Author

This project was built by **Awungjia Sylvester** as part of his cybersecurity upskilling journey.  
Open to roles in **Cybersecurity**, **DevSecOps**, and **Cloud Engineering**.  
Let's connect on [LinkedIn](https://www.linkedin.com/) and grow together!

---

## 🧠 License & Ethics

This project was created for ethical, educational purposes only.  
Only scan hosts that you **own or are authorized to test**.
