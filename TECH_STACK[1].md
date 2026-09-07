# 🛡️ ScamShield — Technologies & Tools Used

ScamShield is a front-end cybersecurity web application that analyzes suspicious messages, emails and links using an explainable rule-based detection engine. This document explains the technologies used to build the project.

> **Important:** The current GitHub version uses a browser-based heuristic/rule engine. It does not claim to be a trained machine-learning model.

---

## 🚀 Technology Stack

### HTML5

<p align="center">
  <img src="assets/tech-stack/html5.svg" alt="HTML5" width="520">
</p>

**Category:** Structure

Used to build the main page structure, forms, navigation, cards, modal windows and dashboard sections.

---

### CSS3

<p align="center">
  <img src="assets/tech-stack/css3.svg" alt="CSS3" width="520">
</p>

**Category:** Styling

Used for the premium dark cyber-security theme, responsive layout, animations, cards, buttons and mobile design.

---

### JavaScript

<p align="center">
  <img src="assets/tech-stack/javascript.svg" alt="JavaScript" width="520">
</p>

**Category:** Logic

Runs ScamShield's scam-analysis engine, risk scoring, tab switching, history, tools and interactive UI.

---

### LocalStorage

<p align="center">
  <img src="assets/tech-stack/localstorage.svg" alt="LocalStorage" width="520">
</p>

**Category:** Browser Storage

Stores scan history, demo user profile and UI preferences directly inside the browser.

---

### Regex Rules

<p align="center">
  <img src="assets/tech-stack/regex.svg" alt="Regex Rules" width="520">
</p>

**Category:** Detection Engine

Matches scam signals such as suspicious links, OTP requests, urgency, prizes, threats and financial requests.

---

### Responsive Design

<p align="center">
  <img src="assets/tech-stack/responsive.svg" alt="Responsive Design" width="520">
</p>

**Category:** Mobile UI

Makes the dashboard adapt to desktops, laptops, tablets and mobile phones.

---

### Cybersecurity Logic

<p align="center">
  <img src="assets/tech-stack/security.svg" alt="Cybersecurity Logic" width="520">
</p>

**Category:** Risk Analysis

Provides explainable scam indicators, risk levels and recommendations to help users understand threats.

---

### GitHub

<p align="center">
  <img src="assets/tech-stack/github.svg" alt="GitHub" width="520">
</p>

**Category:** Version Control

Used to store the source code, documentation, screenshots and project history.

---

## 🧠 How Scam Detection Works

ScamShield checks the text entered by the user for common scam and phishing signals. Each detected signal adds points to a risk score.

| Detection Signal | Example | Risk Weight |
|---|---|---:|
| Urgency Language | “Act now”, “Account blocked” | +18 |
| OTP / Password Request | “Send OTP”, “Enter password” | +30 |
| Suspicious Link | `.xyz`, `.top`, shortened URLs | +22 |
| Prize / Giveaway | “You won”, “Claim reward” | +22 |
| Financial Request | “Transfer money”, “Bank details” | +22 |
| Threat / Fear | “Police action”, “Account suspended” | +16 |
| Personal Data Request | Aadhaar, PAN, KYC details | +20 |
| Impersonation | Bank team, support team, officer | +14 |

### Risk Levels

- **0–17:** Safe
- **18–39:** Low Risk
- **40–69:** Medium Risk
- **70–100:** High Risk

The score is capped at **100** and the app explains which signals caused the score.

---

## ⚙️ Main Functional Features

- Message, email and link analysis
- Explainable 0–100 risk score
- Scam signal detection
- URL checker
- Email-header analyzer
- Scan-history storage
- Threat reports and statistics
- Safety recommendations
- Responsive dashboard
- Demo login/signup interface
- Dark/light appearance support

---

## 📁 Main Project Files

```text
ScamShield/
├── index.html
├── styles.css
├── app.js
├── README.md
├── TECH_STACK.md
├── LICENSE
├── .gitignore
└── assets/
    ├── scamshield-dashboard-preview.png
    └── tech-stack/
        ├── html5.svg
        ├── css3.svg
        ├── javascript.svg
        ├── localstorage.svg
        ├── regex.svg
        ├── responsive.svg
        ├── security.svg
        └── github.svg
```

---

## 🔒 Privacy Approach

The demo performs its core analysis directly inside the browser. Scan history is stored using browser LocalStorage. The current version does not send user messages to an external server.

---

## 🔮 Future Upgrade Stack

For a more advanced production version, ScamShield can be upgraded with:

- **Node.js / Express** — secure backend API
- **Firebase or Supabase** — authentication and database
- **OCR / Vision API** — screenshot scam analysis
- **LLM API** — contextual scam explanation
- **URL reputation API** — malicious-domain verification
- **Cloud deployment** — Vercel, Netlify or similar hosting

Secret API keys should always be stored on a backend or serverless environment and never directly inside frontend JavaScript.

---

## 👨‍💻 Project

**ScamShield — Detect. Prevent. Stay Safe.**

Created by **Shaik Arfan** for cybersecurity learning, hackathons and college demonstrations.
