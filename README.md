🔐 Web Security Scanner Chrome Extension

A lightweight Chrome extension that analyzes website security in real time and alerts users about potential vulnerabilities such as insecure connections, missing security headers, and suspicious elements.

🚀 Features
🔍 Real-time website security scanning
🔒 Detects HTTPS / insecure HTTP usage
⚠️ Identifies missing Content Security Policy (CSP)
🌐 Detects external third-party scripts
🧩 Detects iframe elements (clickjacking risk)
📊 Risk level classification (Low / Medium / High)
🎨 Color-coded results for better understanding
🛠️ Technologies Used
JavaScript
HTML
CSS
Chrome Extension API (Manifest v3)
📁 Project Structure
web-security-extension/
│
├── manifest.json     # Extension configuration
├── popup.html        # UI layout
├── popup.js          # UI logic & messaging
├── content.js        # Core security analysis logic
└── README.md         # Project documentation
⚙️ Installation
Download or clone this repository

Open Chrome and go to:

chrome://extensions/
Enable Developer Mode
Click Load Unpacked
Select the project folder
▶️ Usage
Open any website
Click on the extension icon
Click “Scan Page”
View security analysis and risk level
📸 Screenshots

(Add your project screenshots here)

Popup UI
Scan Results (Secure Site)
Scan Results (Insecure Site)
🧠 How It Works

The extension injects a content script into the active webpage and performs:

HTTPS validation
CSP detection
External script analysis
Iframe detection

A risk score is calculated and displayed with color-coded indicators.

🎯 Project Objective

To improve user awareness about web security by providing a simple, fast, and real-time browser-based analysis tool.

🔮 Future Enhancements
Phishing detection
SSL certificate validation
API-based threat intelligence
Form & password security checks
Dark mode UI
📌 Conclusion

This project demonstrates how browser extensions can be used to detect basic web security issues and promote safe browsing practices in a simple and effective way.
