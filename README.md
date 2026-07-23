## 📌 Overview

The **URL Threat Scanner** is a cybersecurity project developed during our college BCT training. It performs **rule-based URL analysis** to detect potential phishing attempts without relying on machine learning.

Instead of acting as a black-box classifier, the scanner explains **why** a URL is considered suspicious by evaluating multiple structural and lexical indicators.

---

## ✨ Features

- 🔍 URL Structure Analysis
- 🎯 Phishing Risk Score (0-100)
- ⚠️ Explainable Threat Detection
- 🌐 HTTPS Verification
- 🖥️ IP Address URL Detection
- 🎭 Typosquatting Detection
- 🔤 Punycode (IDN Homograph) Detection
- 🚩 Suspicious TLD Detection
- 🔗 URL Shortener Detection
- 📂 Excessive Subdomain Analysis
- 🔑 Credential Harvesting Keyword Detection
- 📊 Interactive Risk Gauge
- 💻 Modern Cybersecurity Dashboard UI

---

## 🛠️ Tech Stack

| Frontend | Backend |
|----------|----------|
| HTML5 | Python |
| CSS3 | Rule-Based Detection Engine |
| JavaScript | Heuristic Analysis |

---

## 🧠 Detection Techniques

The scanner evaluates URLs using multiple cybersecurity heuristics, including:

- Raw IP Address Detection
- HTTPS Validation
- URL Length Analysis
- Suspicious Keywords
- Brand Typosquatting Detection
- Shannon Entropy Analysis
- Excessive Hyphen Detection
- Deep Subdomain Detection
- URL Shortener Detection
- Punycode (IDN) Detection
- Suspicious TLD Detection
- Non-standard Port Detection

Each indicator contributes to a **Risk Score**, producing an easy-to-understand security report.

---

## 📊 Risk Levels

| Score | Verdict |
|--------|---------|
| 🟢 0–14 | Likely Safe |
| 🟡 15–39 | Low Risk |
| 🟠 40–69 | Suspicious |
| 🔴 70–100 | High Risk (Likely Phishing) |

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Sujal-verma777/url-threat-scanner.git
cd url-threat-scanner
```

### Run Backend

```bash
python phishing_detector.py
```

### Launch Frontend

Simply open:

```
index.html
```

in your browser.

---

## 📂 Project Structure

```
URL-Threat-Scanner/
│
├── index.html              # Frontend Dashboard
├── phishing_detector.py    # Detection Engine
├── README.md
└── assets/
```

---

## 🎯 Future Improvements

- Machine Learning Classification
- VirusTotal API Integration
- WHOIS Lookup
- Domain Age Analysis
- DNS Reputation Checks
- Browser Extension
- Email Phishing Scanner
- Dark Mode Enhancements
- Threat Intelligence Feed

---

## 📸 Preview

> *(Add screenshots of your dashboard here.)*

---

## 👨‍💻 Developed By

**BCT Cybersecurity Training Team**

College Project • Cybersecurity • URL Threat Detection

---

## ⭐ If you like this project...

Give it a ⭐ on GitHub and feel free to contribute!
