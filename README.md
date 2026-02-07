# Shannon - AI Pentester for VS Code

<div align="center">
  <a href="https://github.com/tiomxin/shannon/stargazers"><img src="https://img.shields.io/github/stars/tiomxin/shannon?style=for-the-badge&logo=github" alt="GitHub Stars"></a>
  <a href="https://github.com/tiomxin/shannon/network/members"><img src="https://img.shields.io/github/forks/tiomxin/shannon?style=for-the-badge&logo=github" alt="GitHub Forks"></a>
  <a href="https://github.com/tiomxin/shannon"><img src="https://img.shields.io/github/languages/top/tiomxin/shannon?style=for-the-badge" alt="Language"></a>
  <a href="https://github.com/tiomxin/shannon/releases"><img src="https://img.shields.io/github/v/release/tiomxin/shannon?style=for-the-badge&logo=github" alt="Release"></a>
</div>

<div align="center">
  <a href="https://github.com/tiomxin/shannon/actions/workflows/ci.yml"><img src="https://img.shields.io/github/workflow/status/tiomxin/shannon/CI?style=for-the-badge&logo=github" alt="CI Status"></a>
  <a href="https://github.com/tiomxin/shannon/blob/main/LICENSE"><img src="https://img.shields.io/github/license/tiomxin/shannon?style=for-the-badge" alt="License"></a>
  <a href="https://github.com/tiomxin/shannon/pulse"><img src="https://img.shields.io/github/commit-activity/w/tiomxin/shannon?style=for-the-badge" alt="Activity"></a>
</div>

---

<div align="center">
  <a href="https://keygraph.io"><img src="https://raw.githubusercontent.com/KeygraphHQ/shannon/main/assets/shannon-screen.png" alt="Shannon Screen" width="100%"></a>
</div>

---

## 🎯 What is Shannon?

Shannon is an AI-powered pentester that delivers **actual exploits, not just alerts**. Think of it as your autonomous security expert that hunts vulnerabilities before attackers do.

### The Problem We Solve

Your team ships code daily with tools like Claude Code and Cursor, but penetration testing happens once a year. That's 364 days of unknown vulnerabilities. Shannon closes this gap by acting as your on-demand whitebox pentester that **executes real exploits** with proof.

---

## 🚀 Quick Start

```bash
# Install globally
npm install -g @keygraphhq/shannon

# Run against your app
shannon pentest --url https://your-app.com --auth-config auth.json
```

**VS Code Integration**: Right-click any file or folder → "Shannon: Run Security Scan"

---

## 🎬 See Shannon in Action

Shannon discovered **20+ critical vulnerabilities** in OWASP Juice Shop, including complete auth bypass and database exfiltration.

<div align="center">
  <img src="https://raw.githubusercontent.com/KeygraphHQ/shannon/main/assets/shannon-action.gif" alt="Shannon in Action" width="80%">
</div>

[Full Report →](sample-reports/shannon-report-juice-shop.md)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Fully Autonomous** | Launch with one command, AI handles everything from login to final report |
| **VS Code Integration** | Right-click integration for seamless workflow |
| **Real Exploits** | Executes actual attacks, not just theoretical findings |
| **Pentester-Grade Reports** | Reproducible steps with concrete proof |
| **Advanced Auth Handling** | 2FA/TOTP, Google OAuth, session management |
| **Built-in Browser** | Executes exploits in real browser environment |

---

## 🔧 Why This Fork?

This fork by [@tiomxin](https://github.com/tiomxin) adds **VS Code integration** and enhanced developer experience:

- **Right-click integration** in VS Code
- **Enhanced configuration UI**
- **Improved error handling**
- **Additional authentication methods**

---

## 📊 Benchmark Results

Shannon Lite achieves **96.15% success rate** on a hint-free, source-aware XBOW benchmark.

<div align="center">
  <a href="https://github.com/KeygraphHQ/shannon/tree/main/xben-benchmark-results/README.md">
    <img src="https://raw.githubusercontent.com/KeygraphHQ/shannon/main/assets/benchmark-badge.png" alt="96.15% Success Rate" width="300">
  </a>
</div>

---

## 🏗️ Architecture

Shannon combines multiple AI models with browser automation to deliver comprehensive security testing:

- **AI Engine**: Claude-based reasoning for vulnerability discovery
- **Browser Automation**: Puppeteer-based execution of exploits
- **Report Generator**: Structured findings with reproducible steps
- **Auth Manager**: Handles complex authentication scenarios

---

## 📦 Installation

### npm
```bash
npm install -g @keygraphhq/shannon
```

### yarn
```bash
yarn global add @keygraphhq/shannon
```

### VS Code Extension
Install from [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=tiomxin.shannon)

---

## 🛠️ Configuration

```json
{
  "targetUrl": "https://your-app.com",
  "auth": {
    "method": "form",
    "credentials": {
      "username": "user@example.com",
      "password": "password"
    }
  },
  "scanDepth": "deep",
  "reportFormat": "markdown"
}
```

---

## 🤝 Contributing

We welcome contributions! Check out our [contributing guidelines](CONTRIBUTING.md).

### Development Setup

```bash
git clone https://github.com/tiomxin/shannon.git
cd shannon
npm install
npm run dev
```

---

## 🔗 Resources

- **[Official Website](https://keygraph.io)**
- **[Discord Community](https://discord.gg/KAqzSHHpRt)**
- **[Documentation](https://docs.keygraph.io/shannon)**
- **[Original Repository](https://github.com/KeygraphHQ/shannon)**

---

## 📝 License

Shannon is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---

## ⭐ Show Your Support

If you find Shannon useful, please consider starring the repository! Your support helps us continue improving security for everyone.

<div align="center">
  <a href="https://github.com/tiomxin/shannon/stargazers"><img src="https://img.shields.io/github/stars/tiomxin/shannon?style=social&logo=github" alt="GitHub Stars"></a>
  <a href="https://github.com/tiomxin/shannon/fork"><img src="https://img.shields.io/github/forks/tiomxin/shannon?style=social&logo=github" alt="GitHub Forks"></a>
</div>

---

*This fork is maintained by [@tiomxin](https://github.com/tiomxin) and based on the original work by [KeygraphHQ](https://github.com/KeygraphHQ/shannon).*
