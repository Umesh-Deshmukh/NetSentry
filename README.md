# NetSentry

## Defensive Network Vulnerability Scanner

NetSentry is a lightweight, defensive network vulnerability scanner developed in Python. It helps security professionals, students, and network administrators identify common network security issues by performing safe, non-intrusive checks on systems they own or are authorized to test.

---

## Features

- TCP Port Scanning with configurable port ranges
- Banner Grabbing for common network services
- HTTP and HTTPS Security Checks
- Missing Security Header Detection
- TLS/SSL Certificate Information Collection
- Simple Risk Scoring
- Vulnerability Findings Report
- Built-in Web Dashboard
- JSON API Support
- Command Line (CLI) Mode
- Cross-platform support (Windows & Linux)

---

## Technologies Used

- Python 3.10+
- HTML5
- CSS3
- JavaScript
- HTTP Server
- Socket Programming
- Git
- GitHub

---

## Project Structure

```
NetSentry
│── app.py
│── launcher.py
│── scanner.py
│── README.md
│── run-windows.bat
│── run-windows.ps1
│── run-linux.sh
│── static/
│   ├── index.html
│   ├── app.js
│   └── styles.css
```

---

## Requirements

- Python 3.10 or newer
- Windows 10/11 or Linux
- No third-party Python packages required

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Umesh-Deshmukh/NetSentry.git
```

Go to the project folder:

```bash
cd NetSentry
```

---

## Running the Application

### Windows

Using PowerShell:

```powershell
.\run-windows.ps1
```

Or using Batch:

```cmd
run-windows.bat
```

Or directly:

```bash
python app.py
```

### Linux

```bash
chmod +x run-linux.sh
./run-linux.sh
```

---

## Web Interface

After starting the application, open your browser and visit:

```
http://127.0.0.1:8080
```

or

```
http://localhost:8080
```

---

## Scanner Capabilities

- Detect Open TCP Ports
- Identify Running Services
- Perform Banner Grabbing
- Check HTTP Security Headers
- Inspect HTTPS Configuration
- Collect SSL/TLS Certificate Metadata
- Generate Basic Security Findings
- Display Results in a Web Dashboard

---

## Usage

1. Start the application.
2. Open the browser interface.
3. Enter the target IP address or hostname.
4. Select the port range.
5. Start the scan.
6. Review the findings.

> **Important:** Only scan systems that you own or have explicit authorization to test.

---

## Security Notice

NetSentry is intended exclusively for defensive security testing and educational purposes. Unauthorized scanning of networks or systems may violate laws or organizational policies. Always obtain permission before scanning any target.

---

## Future Improvements

- User Authentication
- Scan History
- PDF Report Generation
- CSV Export
- Dark Mode
- Database Integration
- CVE Lookup
- Nmap Integration
- Docker Support
- Multi-user Dashboard

---

## Author

**Umesh Deshmukh**

Cyber Security & Digital Forensics Engineer

**GitHub:** https://github.com/Umesh-Deshmukh

**Email:** umeshdeshmukh9795@gmail.com

---

## License

This project is intended for educational and defensive security purposes.
