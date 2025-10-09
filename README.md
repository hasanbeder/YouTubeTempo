# 🎬 YouTubeTempo
> **Ultimate YouTube Playback Speed Controller**

<div align="center">

![YouTubeTempo Screenshot](https://raw.githubusercontent.com/hasanbeder/YouTubeTempo/main/screenshots/screenshot.png)

[![Version](https://img.shields.io/badge/version-1.0.1-2196F3.svg?style=flat-square&logo=github&logoColor=white)](https://github.com/hasanbeder/YouTubeTempo/releases)
[![License](https://img.shields.io/badge/license-GPL--3.0-4CAF50.svg?style=flat-square&logo=gnu&logoColor=white)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hasanbeder/YouTubeTempo?style=flat-square&logo=github&logoColor=white&color=FFD700)](https://github.com/hasanbeder/YouTubeTempo/stargazers)
[![Greasyfork](https://img.shields.io/badge/Greasyfork-Install-FF5722.svg?style=flat-square&logo=javascript&logoColor=white)](https://greasyfork.org/en/scripts/542866-youtubetempo-ultimate-playback-speed-controller)

</div>

<div align="center">
  <h3>🎯 Master your YouTube experience with precision speed controls!</h3>
  <p><em>Take complete control of YouTube playback with fully customizable speed controls, keyboard shortcuts, and a clean, accessible interface designed for performance.</em></p>
</div>

---

## ✨ Features

### 🎛️ Precision Speed Control 
- **Custom Speed Steps**: Set your preferred increment from 0.01x to 0.5x. 
- **Wide Playback Range**: Freely adjust speed from as low as 0.1x up to 16.0x. 
- **Instant Visual Feedback**: The speed indicator changes color to reflect the current playback rate. 
- **Playback Memory**: Remembers and automatically applies your last-used speed setting for new videos. 

### ⌨️ Fully Customizable Keyboard Shortcuts 
- **Personalize Your Keys**: Assign any key for slowing down, speeding up, or resetting playback speed. 
- **Sensible Defaults**: Comes pre-configured with `[` (slower), `]` (faster), and `\` (reset). 
- **Override Mode**: Optionally prevent your shortcuts from triggering YouTube's default actions. 
- **Mouse-Free Control**: Manage playback speed without ever leaving the keyboard. 

### 🎨 Clean & Integrated User Interface 
- **Seamless Design**: The controls are designed to perfectly match YouTube's native player aesthetic. 
- **Accessible**: Built with ARIA attributes for screen reader compatibility. 
- **Collapsible Settings Menu**: Access all options in a clean, non-intrusive popup menu. 
- **Audio Feedback**: Enable or disable subtle sound effects for speed adjustments.

---

## 🚀 Quick Start

### 📦 Installation

<div align="center">

| Method | Description | Link |
|--------|-------------|------|
| **🟢 Greasyfork** | Recommended | [![Install](https://img.shields.io/badge/Install-Greasyfork-FF5722.svg?style=for-the-badge&logo=javascript&logoColor=white)](https://greasyfork.org/en/scripts/542866-youtubetempo-ultimate-playback-speed-controller) |
| **📁 GitHub** | Latest version | [![Download](https://img.shields.io/badge/Download-GitHub-181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/hasanbeder/YouTubeTempo/main/YouTubeTempo.user.js) |

</div>

### 🛠️ Prerequisites

Install a userscript manager first:

<div align="center">

[![Tampermonkey](https://img.shields.io/badge/Tampermonkey-00485B.svg?style=for-the-badge&logo=tampermonkey&logoColor=white)](https://tampermonkey.net/)
[![Violentmonkey](https://img.shields.io/badge/Violentmonkey-8E44AD.svg?style=for-the-badge&logo=violentmonkey&logoColor=white)](https://violentmonkey.github.io/)
[![Greasemonkey](https://img.shields.io/badge/Greasemonkey-FF6600.svg?style=for-the-badge&logo=firefox&logoColor=white)](https://addons.mozilla.org/firefox/addon/greasemonkey/)

</div>

---

## 🎯 Usage

### 🎮 Basic Controls

```
1. 🎬 Navigate to any YouTube video
2. 🔍 Look for YouTubeTempo controls next to volume slider
3. ⚡ Use speed control buttons (◀ slower, ▶ faster) to adjust speed
4. ⚙️ Click speed indicator to open settings
```

### ⌨️ Keyboard Shortcuts

<div align="center">

| Key | Action | Status |
|-----|--------|--------|
| `[` | **Decrease Speed** | ✅ Customizable |
| `]` | **Increase Speed** | ✅ Customizable |
| `\` | **Reset to 1.0x** | ✅ Customizable |
| *Click Speed* | **Open Settings** | 🔒 Fixed |

</div>

### ⚙️ Advanced Configuration

<details>
<summary><strong>🎛️ Speed Settings</strong></summary>

- **Speed Step**: Increment size (0.01x - 0.5x)
- **Min Speed**: Lowest allowed speed (0.1x - 1.0x)
- **Max Speed**: Highest allowed speed (1.0x - 16.0x)

</details>

<details>
<summary><strong>🎨 General & UI Settings</strong></summary>

- **Remaining Time**: Show time left calculation
- **Color Indicators**: Speed-based color coding

</details>

---

## 🔧 Troubleshooting

<details>
<summary><strong>❌ YouTubeTempo not appearing</strong></summary>

- 🔄 Refresh the YouTube page
- ✅ Check if userscript manager is enabled
- 🔍 Verify script is installed and active
- 🔒 Try incognito/private browsing mode

</details>

<details>
<summary><strong>⚡ Speed not changing</strong></summary>

- 🎬 Click directly on the video player
- 🔍 Check for extension conflicts
- 🔄 Disable and re-enable the script
- 🎯 Ensure video player has focus

</details>

<details>
<summary><strong>⌨️ Keyboard shortcuts not working</strong></summary>

- ⚙️ Enable "Override YouTube Shortcuts" in settings
- 🔍 Check for shortcut conflicts
- 🎯 Ensure video player has focus
- 🔄 Try refreshing the page

</details>



---

## 🌐 Browser Support

<div align="center">

| Browser | Support | Notes |
|---------|---------|-------|
| ![Chrome](https://img.shields.io/badge/Chrome-4285F4.svg?style=flat-square&logo=google-chrome&logoColor=white) | **✅ Full** | Recommended |
| ![Firefox](https://img.shields.io/badge/Firefox-FF7139.svg?style=flat-square&logo=firefox&logoColor=white) | **✅ Full** | Excellent |
| ![Safari](https://img.shields.io/badge/Safari-000000.svg?style=flat-square&logo=safari&logoColor=white) | **✅ Full** | Supported |
| ![Edge](https://img.shields.io/badge/Edge-0078D4.svg?style=flat-square&logo=microsoft-edge&logoColor=white) | **✅ Full** | Supported |
| ![Opera](https://img.shields.io/badge/Opera-FF1B2D.svg?style=flat-square&logo=opera&logoColor=white) | **✅ Full** | Supported |

</div>

---

## 🤝 Contributing

<div align="center">

We welcome contributions! Here's how you can help:

[![Issues](https://img.shields.io/badge/Report%20Bug-GitHub%20Issues-FF4444.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hasanbeder/YouTubeTempo/issues)
[![Feature Request](https://img.shields.io/badge/Request%20Feature-GitHub%20Issues-4CAF50.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hasanbeder/YouTubeTempo/issues)
[![Pull Request](https://img.shields.io/badge/Submit%20PR-GitHub%20PR-2196F3.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hasanbeder/YouTubeTempo/pulls)

</div>

### 💡 Ways to Contribute

- 🐛 **Report bugs** via GitHub Issues
- 💡 **Suggest features** via GitHub Issues  
- 🔧 **Submit pull requests** for fixes and improvements
- 📖 **Improve documentation** and help others
- 🌍 **Help with translations** for your language

---

## 📄 License

<div align="center">

This project is licensed under the **GPL-3.0 License**

[![License](https://img.shields.io/badge/License-GPL%20v3-blue.svg?style=for-the-badge&logo=gnu&logoColor=white)](LICENSE)

</div>

---

## 💝 Support

<div align="center">

[![GitHub Issues](https://img.shields.io/badge/Issues-GitHub-181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hasanbeder/YouTubeTempo/issues)
[![GitHub Discussions](https://img.shields.io/badge/Discussions-GitHub-181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hasanbeder/YouTubeTempo/discussions)
[![Contact](https://img.shields.io/badge/Contact-@hasanbeder-1DA1F2.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hasanbeder)

</div>

---

<div align="center">
  <h3>🙏 Acknowledgments</h3>
  <p>Thanks to <strong>YouTube</strong> for the amazing platform • <strong>Userscript community</strong> for inspiration • <strong>All contributors</strong> who make this project better</p>
</div>

<div align="center">
  <h3>Made with ❤️ by <a href="https://github.com/hasanbeder">Hasan Beder</a></h3>
  <p>⭐ <strong>Star this repo if you find it useful!</strong></p>
</div>
