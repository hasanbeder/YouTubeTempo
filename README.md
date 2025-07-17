# 🎬 YouTubeTempo
> **Ultimate YouTube Playback Speed Controller**

<div align="center">

![YouTubeTempo Screenshot](https://raw.githubusercontent.com/hasanbeder/YouTubeTempo/main/screenshots/screenshot.png)

[![Version](https://img.shields.io/badge/version-1.0.0-2196F3.svg?style=flat-square&logo=github&logoColor=white)](https://github.com/hasanbeder/YouTubeTempo/releases)
[![License](https://img.shields.io/badge/license-GPL--3.0-4CAF50.svg?style=flat-square&logo=gnu&logoColor=white)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hasanbeder/YouTubeTempo?style=flat-square&logo=github&logoColor=white&color=FFD700)](https://github.com/hasanbeder/YouTubeTempo/stargazers)
[![Greasyfork](https://img.shields.io/badge/Greasyfork-Install-FF5722.svg?style=flat-square&logo=javascript&logoColor=white)](https://greasyfork.org/en/scripts/542866-youtubetempo-ultimate-playback-speed-controller)

</div>

<div align="center">
  <h3>🎯 Master your YouTube experience with precision speed controls!</h3>
  <p><em>Take complete control of YouTube playback with fully customizable speed controls, volume booster, keyboard shortcuts, and a clean, accessible interface.</em></p>
</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎛️ **Precision Speed Control**
- **Custom Speed Steps**: 0.01x to 0.5x increments
- **Wide Range**: 0.1x to 16.0x configurable speed
- **Visual Feedback**: Color-coded indicators
- **Memory**: Remembers your last used speed

### 🔊 **Volume Enhancement**
- **Volume Booster**: Amplify beyond 100%
- **Web Audio API**: Professional audio processing
- **Safe Limits**: Prevents audio distortion
- **Real-time**: Instant volume adjustments

</td>
<td width="50%">

### ⌨️ **Keyboard Shortcuts**
- **Fully Customizable**: Set your own shortcuts
- **Default Keys**: `[` slower, `]` faster, `\` reset
- **Override Mode**: Disable YouTube's shortcuts
- **Quick Access**: No mouse required

### 🎨 **Clean Interface**
- **Seamless Integration**: Matches YouTube's design
- **Accessibility**: Full ARIA support
- **Collapsible Menu**: Expandable settings
- **Visual Indicators**: Real-time feedback

</td>
</tr>
</table>

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
<summary><strong>🔊 Audio Settings</strong></summary>

- **Volume Boost**: Amplification level (1.0x - 3.0x)
- **Sound Effects**: Enable/disable UI sounds
- **Audio Context**: Professional audio processing

</details>

<details>
<summary><strong>🎨 Display Settings</strong></summary>

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

<details>
<summary><strong>🔊 Volume boost not working</strong></summary>

- 🔓 Allow audio permissions when prompted
- 🌐 Check Web Audio API browser support
- 🔄 Try refreshing the page
- 📱 Test on different browser

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
