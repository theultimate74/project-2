# 🛡️ Web Vulnerability Scanner

A Python-based tool to identify **common vulnerabilities** in web applications, such as:

- 🐞 **SQL Injection (SQLi)**
- 💉 **Cross-Site Scripting (XSS)**

This scanner parses HTML forms, injects malicious payloads, and analyzes responses to detect potential vulnerabilities.

---

## ⚙️ Features

- ✅ Detects SQL Injection and XSS in form fields
- ✅ Scans GET and POST forms
- ✅ Checks URL query parameters
- ✅ Uses `requests` and `BeautifulSoup`
- ✅ Clean and readable CLI output

---

## 🚀 Getting Started

### 📦 Requirements

- Python 3.x
- Install dependencies:
  
```bash
pip install requests beautifulsoup4
