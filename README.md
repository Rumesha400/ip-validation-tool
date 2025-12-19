# 🌐 IP Address Validation & Network Check Tool

A Python-based command-line tool that validates IP addresses in **decimal** and **binary** formats, converts between formats, checks **network reachability**, and resolves **hostnames** using Python’s built-in `socket` module.

---

## 🚀 Features

- ✅ Validates **decimal IPv4 addresses**
- ✅ Validates **binary IPv4 addresses**
- ✅ Accepts IPs **with or without dots**
- 🔄 Converts binary IPs to decimal format
- 🌍 Checks **network reachability** (port 80)
- 🏷️ Resolves **hostname** from IP address
- 🧭 Interactive **menu-driven CLI**
- ⚠️ Graceful handling of invalid inputs

---

## 🧠 How It Works

### Supported Input Formats
- Decimal with dots: `192.168.1.1`
- Decimal without dots: `192168001001`
- Binary with dots: `11000000.10101000.00000001.00000001`
- Binary without dots: `11000000101010000000000100000001`

### Validations Performed
- Checks correct IPv4 structure
- Ensures decimal values are between `0–255`
- Ensures binary values are exactly `8 bits`
- Converts binary IPs to decimal format
- Tests network reachability using socket connection
- Resolves hostname using reverse DNS lookup

---
├── ip_validation_tool.py
├── README.md

---

## 🛠️ Requirements

- Python 3.x
- No external libraries required (uses built-in `socket` module)

---

## ▶️ How to Run

Clone the repository:
git clone https://github.com/Rumesha400/ip-validation-tool.git


Navigate to the project directory:
cd ip-validation-tool


Run the program:
python ip_validation_tool.py


---

## 🧪 Usage

Menu Options:
1. Validate an IP Address

2. Exit
## 

When prompted, enter an IP address in decimal or binary format.  
The tool will validate, convert (if needed), check reachability, and resolve hostname.

---

## 📄 Sample Output
Valid decimal IP address: 8.8.8.8
Reachability: Reachable
The IP 8.8.8.8 resolves to hostname: dns.google
Validation completed.

---

## 📌 Use Cases

- Networking fundamentals practice
- IP address validation utilities
- Academic mini-projects
- Python socket programming demonstrations

---

## 🔮 Future Enhancements

- Support for IPv6
- Custom port reachability checks
- Timeout configuration
- Logging support
- GUI or web-based interface

---

## 👩‍💻 Author

Rumesh  
GitHub: https://github.com/Rumesha400

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you find this project useful, consider giving it a star!

📁 Project Structure

