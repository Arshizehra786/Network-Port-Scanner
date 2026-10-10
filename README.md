# Network Port Scanner 🔍

## 📌 About the Project
The **Network Port Scanner** is a cybersecurity project that uses Nmap on Kali Linux to scan authorized target systems, identify open ports, detect running services, and assess potential network security risks.

## 🎯 Objectives
- Identify open, closed, and filtered ports.
- Discover services running on a target host.
- Understand network reconnaissance.
- Analyze network exposure and potential security risks.
- Document scanning results for security assessment.

## 🛠️ Tools & Technologies
- **Operating System:** Kali Linux
- **Scanning Tool:** Nmap
- **Category:** Cybersecurity / Network Security

## ⚙️ Installation

Update the package list:

```bash
sudo apt update
```

Install Nmap:

```bash
sudo apt install nmap
```

Verify installation:

```bash
nmap --version
```

## 🚀 How to Use

### 1. Scan a Target Host

```bash
nmap <target-ip>
```

### 2. Scan Specific Ports

```bash
nmap -p 22,80,443 <target-ip>
```

### 3. Detect Running Services and Versions

```bash
nmap -sV <target-ip>
```

**Note:** Replace `<target-ip>` with the IP address of a system you own or are explicitly authorized to test.

## ✨ Key Features
- TCP port scanning
- Port status identification
- Service and version detection
- Network reconnaissance
- Security assessment and result documentation

## 📁 Project Structure

```text
Network-Port-Scanner/
├── README.md
├── screenshots/
└── reports/
```

Add screenshots and reports after completing your scan.

## 📈 Learning Outcomes
- Understanding network ports and services
- Hands-on experience with Nmap
- Learning basic network reconnaissance techniques
- Interpreting scan results and identifying exposed services

## ⚠️ Disclaimer
This project is intended for educational purposes and authorized security testing only. Never scan systems without appropriate permission.

## 👩‍💻 Author
**Arshi**  
Aspiring Cybersecurity Analyst
