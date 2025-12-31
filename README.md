# PyCyberSuite 🔐
PyCyberSuite is an all-in-one Python Cybersecurity Toolkit with a modern Tkinter GUI.  
It integrates multiple security modules including network scanning, subdomain enumeration, password analysis, brute-force simulation, encryption tools, automation, and reporting — built strictly for **ethical and educational cybersecurity use**.

---

## 🚀 Features
✔ Secure Authentication System (JSON user database)  
✔ Network Scanner (Nmap based – open ports & host detection)  
✔ Subdomain Enumerator (wordlist based)  
✔ Password Strength & Breach Checker  
✔ Encryption Toolkit (Symmetric & Asymmetric)  
✔ Brute Force Simulator  
✔ Dictionary Attack Engine  
✔ Automation & Scheduling Support  
✔ Detailed JSON Report Generator  

---

## 🧠 Tech Stack
- Python 3.8+
- Tkinter (GUI)
- Cryptography
- Requests
- python-nmap
- schedule

---

## 📂 Project Structure
```
main.py                      # Main GUI application
requirements.txt             # Python dependencies
modules/                     # All core modules
    auth.py                  # Authentication logic
    automation.py            # Automation and scheduling
    brute_force_sim.py       # Brute force simulation
    crypto_tools.py          # Encryption tools
    dictionary_attack.py     # Dictionary attack logic
    network_scanner.py       # Network scanning
    password_checker.py      # Password analysis
    report_generator.py      # Report generation
    subdomain_file.py        # Subdomain enumeration
    __init__.py              # Module init
    __pycache__/             # Python cache files
reports/                     # Saved reports
data/                        # Data files
    demo_wordlist.txt        # Password wordlist
    user.json                # User database
    wordlists/
        sub_wordlist.txt     # Subdomain wordlist
        ...                  # Other wordlists

```

## Installation

1. Clone the repository:
   ```powershell
   git clone https://github.com/HarvinderSingh22/PyCyberSuite.git
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```

## Usage

Run the main application:
```powershell
python main.py
```
Login credentials are stored in `data/user.json`.

Reports are saved in the `reports/` directory.

---

## 📝 Notes
This toolkit is strictly for:
- Educational Learning  
- Ethical Cybersecurity Testing  

❌ Do NOT use for unauthorized penetration testing.

---

## 🤝 Contributing
Pull requests are welcome!  
Report issues and suggest enhancements anytime.

---

## 📜 License
MIT License


---

**Note:** This toolkit is for educational and ethical use only. Do not use it for unauthorized penetration testing or attacks.
