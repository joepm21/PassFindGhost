Password Finder - Encrypted Credential Manager

📖 Description

Password Finder is a powerful and secure desktop application designed for security professionals, pentesters, and system administrators to efficiently search, manage, and protect credential databases. Built with Python and featuring a hacker-style interface, it provides robust encryption support and advanced search capabilities for handling sensitive credential information.

🚀 Key Features

🔍 Advanced Search Engine

 - Real-time credential searching with aircrack-ng style animations
 - Multi-field search capability across sites, users, and passwords
 - Regex-powered pattern matching for flexible querying
 - Instant results with live filtering

🔒 Military-Grade Encryption

 - AES-256 CBC encryption for secure file storage
 - PBKDF2 key derivation with 100,000 iterations
 - In-memory decryption - no temporary files created
 - Full compatibility with custom encryption scripts
 - Secure password handling with hidden input fields

💻 Professional Interface

 - Hacker-style terminal with green/black color scheme
 - Context-aware UI with intelligent button management
 - Real-time statistics and search metrics
 - Responsive design with scrollable results

📊 Smart Data Management

 - Multiple format support (.txt, .encrypted)
 - Bulk operations with clear all functionality
 - Clipboard integration for quick credential copying
 - Structured data parsing with automatic field detection

🛠️ Technical Specifications

Architecture

- Frontend: Tkinter with ttk widgets
- Cryptography: cryptography.hazmat (AES-256, PBKDF2)
- Threading: Non-blocking search operations
- Pattern Matching: Regular expressions with case-insensitive search

🎯 Use Cases

🔐 Security Professionals

 - Penetration Testing: Manage credentials discovered during engagements
 - Incident Response: Quickly search through credential dumps
 - Forensic Analysis: Organize and analyze compromised credentials

👨‍💼 System Administrators
 
 - Credential Auditing: Search through password databases
 - Emergency Access: Secure storage of backup credentials
 - Compliance: Maintain encrypted records of service accounts

🔬 Security Researchers
 
 - Data Breach Analysis: Process and search through leaked databases
 - Pattern Recognition: Identify common password structures
 - Research Datasets: Manage large credential collections securely

📦 Installation & Requirements

Python 3.8+
cryptography library
tkinter (usually included with Python)

Installation 

download the binary in release

https://github.com/joepm21/PassFindGhost/releases/tag/cryptography

Install dependencias force

    pip install cryptography --break-system-packages
    chmod +x PassFindGhost
    ./PassFindGhost

🖥️ Usage Guide

Basic Workflow

1. Select File: Use "Browse" to choose your credential database.
2. Load Data:
  - Plain text: Click "Load"
  - Encrypted: Enter password → "Load Encrypted"
3. Search: Enter site name and click "Search"
4. Manage: Use right-click context menu to copy credentials

📸 Screenshots

<img width="711" height="578" alt="image" src="https://github.com/user-attachments/assets/a5271758-8c88-4974-afb6-f5a241724d10" />

🛠️ Technical Details
- Supported Formats
  # Plain Text:
      google.com    user@gmail.com    password123
      github.com    developer@gh.com  securepass!

Advanced Features

 - Quick Search: Press Enter in search field for instant results
 - Bulk Operations: "Clear All" resets entire application state
 - Secure Copy: Context menu options for selective data copying

To convert a file.txt to encrypted I use this tool

    https://github.com/joepm21/cryptom4n

🛡️ Security Considerations

Best Practices

✅ Always use strong, unique passwords for encryption
✅ Store encrypted files in secure locations
✅ Clear application state after use
✅ Keep the application updated

DEMO VIDEO 

https://dai.ly/x9rr1su

⚠️ Disclaimer
This tool is intended for legitimate security research, penetration testing, and authorized auditing purposes only. Users are responsible for complying with all applicable laws and regulations.

👨‍💻 Author
Created by j03 💀
