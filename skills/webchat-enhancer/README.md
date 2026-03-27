# WebChat Enhancer

🌟 **One-click navigation for OpenClaw WebChat**

Transform your OpenClaw chat experience with clickable message navigation, 4 languages, and 3 beautiful themes.

---

## ⚡ One-Command Install

```bash
curl -sL https://raw.githubusercontent.com/yjin94606-art/webchat-enhancer/main/skills/webchat-enhancer/install.sh | bash
```

---

## Requirements

- **OpenClaw** running on `http://127.0.0.1:18789`
- **Tampermonkey** browser extension

### Install Tampermonkey

| Browser | Install |
|---------|---------|
| Chrome | [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey) |
| Firefox | [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) |
| Edge | [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/tampermonkey) |
| Safari | [Safari Tampermonkey](https://safari.tampermonkey.net/) |

### ⚠️ Chrome: Enable Developer Mode

If using Chrome, you must enable Developer Mode:

1. Open `chrome://extensions/`
2. Toggle **Developer Mode** ON (top right)
3. Reload Tampermonkey extension
4. Refresh WebChat page

---

## Installation

### Option 1: GreasyFork (Recommended)

```bash
open "https://greasyfork.org/zh-CN/scripts/571337-webchat-enhancer"
```

Click the green **"Install"** button.

### Option 2: Manual

1. Download: [enhancer.user.js](https://raw.githubusercontent.com/yjin94606-art/webchat-enhancer/main/skills/webchat-enhancer/scripts/enhancer.user.js)
2. Open Tampermonkey Dashboard
3. Create new script → Paste code → Save

---

## Preview

```
┌─────────────────────────────┐
│ 📑 Chat Navigator     [12]  │
├─────────────────────────────┤
│ ┌─────────────────────────┐ │
│ │ 1  How to optimize...  │ │
│ └─────────────────────────┘ │
│ ┌─────────────────────────┐ │
│ │ 2  Let me help you...   │ │
│ └─────────────────────────┘ │
│ ┌─────────────────────────┐ │
│ │ 3 ✅ Latest message     │ │
│ └─────────────────────────┘ │
├─────────────────────────────┤
│   🔄 Refresh   ⚙️ Settings  │
└─────────────────────────────┘
```

---

## Features

| Feature | Description |
|---------|-------------|
| 📑 **Clickable Navigation** | Jump to any conversation segment |
| 🌐 **4 Languages** | English · 中文 · 日本語 · 한국어 |
| 🎨 **3 Themes** | Dark · Light · Gradient |
| ⚡ **Auto-scan** | Automatically generates navigation |
| 💾 **Persistent** | Settings saved locally |

---

## Usage

| Action | Effect |
|--------|--------|
| Click title bar | Collapse/expand panel |
| Drag title bar | Move panel position |
| Click any card | Jump to that message |
| 🔄 Refresh | Rescan conversation |
| ⚙️ Settings | Change language/theme |

---

## Troubleshooting

**Script not working?**
1. Make sure Tampermonkey icon is **colored** (not gray)
2. Enable **Developer Mode** in Chrome (`chrome://extensions/`)
3. Refresh WebChat page and wait 3 seconds

---

## Links

- 🌐 [ClawHub](https://clawhub.com/skills/webchat-enhancer)
- 📦 [GreasyFork](https://greasyfork.org/zh-CN/scripts/571337-webchat-enhancer)
- 💻 [GitHub](https://github.com/yjin94606-art/webchat-enhancer)

---

<p align="center">
  Made with ❤️ for better OpenClaw experience
</p>
