# 🛡️ ScamShield

<p align="center">
  <img src="assets/scamshield-dashboard-preview.png" alt="ScamShield dashboard preview" width="900">
</p>

**ScamShield** is a cybersecurity web app that analyzes suspicious SMS messages, emails and URLs. It detects common phishing/scam signals, calculates an explainable **0–100 risk score**, and gives safety recommendations.

> **Hackathon transparency:** Version 1.0 uses a browser-based heuristic/rule engine. It is not a trained ML model and the screenshot/image input is currently a demo workflow without OCR.

## ✨ Features

- Message, email and URL analysis
- Explainable risk score and risk level
- OTP/password, urgency, suspicious-link, prize, financial-request and impersonation detection
- Scan history using browser LocalStorage
- URL checker and basic email-header analyzer
- Reports/dashboard views
- Safety tips
- Responsive dark cybersecurity UI
- Demo login/signup interface and appearance toggle

## 🚀 Run locally

### Fastest method
Open `index.html` in a modern browser.

### Local development server
```bash
npm install
npm start
```

Then open the local URL shown in your terminal.

## 🧪 JavaScript check

```bash
npm run check
```

## 📁 Repository structure

```text
ScamShield/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── workflows/
│   └── PULL_REQUEST_TEMPLATE.md
├── assets/
├── docs/
├── sample-data/
├── .env.example
├── .gitignore
├── app.js
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── index.html
├── LICENSE
├── package.json
├── README.md
├── SECURITY.md
├── styles.css
└── TECH_STACK.md
```

## 🔐 Privacy

Core v1 analysis runs in the browser. Scan history and demo profile settings use LocalStorage. Do not put API keys or secrets in frontend JavaScript.

## 📚 Documentation

See [`docs/`](docs/) for usage, architecture, deployment and roadmap guides. See [`TECH_STACK.md`](TECH_STACK.md) for technologies and risk-rule details.

## 🌐 GitHub Pages

This static app can be hosted with GitHub Pages. The included Pages workflow can deploy the repository after you enable **Settings → Pages → Source: GitHub Actions**.

## 🤝 Contributing

Read [`CONTRIBUTING.md`](CONTRIBUTING.md), [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md), and [`SECURITY.md`](SECURITY.md) before contributing.

## 📄 License

Released under the MIT License. See [`LICENSE`](LICENSE).

## 👨‍💻 Creator

Created by **Shaik Arfan** for cybersecurity learning, hackathons and college demonstrations.

**ScamShield — Detect. Prevent. Stay Safe.**
