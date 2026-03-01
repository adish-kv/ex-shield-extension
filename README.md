# 🛡 Ex-Shield

Ex-Shield is a Chrome Extension Risk Detection System that analyzes installed browser extensions and evaluates their security risk based on permission sensitivity.

## 🚀 Features

- 🔍 Scan installed Chrome extensions
- 🧠 Risk scoring engine based on sensitive permissions
- 📊 Interactive dashboard (High / Medium / Low filtering)
- 🛑 Enable / Disable extensions directly
- 📄 Export professional PDF security report
- 🎨 Cyber-themed UI (Space Grotesk + JetBrains Mono)

## 🧠 Risk Model

Sensitive permissions are weighted:
- debugger (+50)
- webRequest (+40)
- webRequestBlocking (+40)
- <all_urls> (+30)
- cookies (+25)
- scripting (+20)
- history (+20)
- tabs (+15)

Risk classification:
- HIGH > 70
- MEDIUM > 30
- LOW ≤ 30

## 🏗 Built With

- Chrome Extension Manifest v3
- JavaScript
- Custom raw PDF generator (MiniPDF)
- Modern CSS animations

## 📦 Installation (Developer Mode)

1. Clone repository
2. Open Chrome → chrome://extensions
3. Enable Developer Mode
4. Click "Load Unpacked"
5. Select project folder

---

⚠ This tool is for educational and security awareness purposes.
