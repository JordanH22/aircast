# AirCast

### Premium IPTV Streaming for macOS & Apple TV

AirCast is a next-generation IPTV client built natively for Apple platforms. Engineered from the ground up with Swift and Metal, it delivers a premium TV viewing experience with intelligent channel management, hardware-accelerated playback, and a UI that feels right at home on your Mac and Apple TV.

---

## ✨ Features

### 🖥️ macOS
- **Native macOS App** — Built with SwiftUI for macOS 14+
- **AirPlay Integration** — Cast to any AirPlay-compatible device
- **Picture-in-Picture** — Keep watching while you work
- **Intelligent TV Guide** — Smart EPG deduplication with real programme data
- **Multi-Source Quality Picker** — Choose your preferred stream quality and provider
- **HEVC/H.265 Hardware Decoding** — Smooth 4K playback with minimal CPU usage
- **HDR Support** — Full HDR10 and HLG support on compatible displays
- **VLC Playback Engine** — Dual-engine architecture with AVPlayer + VLC fallback
- **Stream Diagnostics** — Real-time bitrate, codec, and network monitoring
- **Mini Player** — Floating overlay that follows you across tabs

### 📺 Apple TV
- **Siri Remote Optimised** — First-class focus navigation
- **Sky Q-Inspired UI** — Tab-based navigation with Sports, Movies, On Demand
- **Favourites System** — Quick access to your most-watched channels  
- **Smart Search** — Find channels instantly across your entire lineup
- **VOD Library** — Browse and stream on-demand movies and series
- **Quality Picker** — Liquid Glass overlay for stream source selection
- **Full-Screen Player** — Native tvOS playback with transport controls

### 🔧 Under the Hood
- **Smart EPG Engine** — Matches raw IPTV channels to real TV guide data
- **Xtream Codes API** — Full compatibility with Xtream-based providers
- **Sentient Channel Matcher** — AI-powered channel name normalisation
- **UK Channel Ordering** — Automatic Freeview/Sky logical channel numbers
- **Anti-Buffering** — Intelligent stream source failover
- **ProMotion Support** — 120Hz UI rendering on compatible displays

---

## 📥 Download

| Platform | Download | Requirements |
|---|---|---|
| **macOS** | [Download DMG](https://github.com/JordanH22/aircast/releases/latest) | macOS 14.0 (Sonoma) or later |
| **Apple TV** | [Download IPA](https://github.com/JordanH22/aircast/releases/latest) | tvOS 17.0 or later |

### macOS Installation
1. Download `AirCast-macOS.dmg` from the latest release
2. Open the DMG and drag **AirCast** to your Applications folder
3. Launch AirCast from Applications
4. If macOS shows a security prompt, go to **System Settings → Privacy & Security** and click **Open Anyway**

### Apple TV Installation
AirCast for Apple TV is distributed as a sideloadable `.ipa` file. You can install it using:
- **Apple Configurator 2** (Mac App Store, free)
- **Sideloadly** ([sideloadly.io](https://sideloadly.io))
- **Xcode** via Devices & Simulators

> **Note:** Sideloaded apps need to be re-signed every 7 days with a free Apple ID, or 365 days with a paid Apple Developer account.

---

## 🔑 Licensing

AirCast includes a **14-day free trial** with full functionality. After the trial, a license key is required.

| Plan | Price | Details |
|---|---|---|
| **Annual** | £7.99/year | [Purchase →](https://buy.stripe.com/cNiaEQ8Htb78cPDebrcbC00) |
| **Lifetime** | £19.99 once | [Purchase →](https://buy.stripe.com/8x27sE3n9grseXL0kBcbC01) |

- ✅ One license covers **both macOS and Apple TV**
- ✅ Activate on up to **3 devices**
- ✅ Instant delivery — your license key is displayed immediately after purchase
- ✅ Secure payment via Stripe

### Activating Your License
1. Purchase a license using one of the links above
2. Copy your license key from the thank-you page
3. Open AirCast and paste the key in the activation screen
4. That's it — you're in!

---

## 🛡️ Privacy

AirCast does not collect, store, or transmit any personal data. Your IPTV credentials are stored locally on your device. License validation is performed via a secure API that only checks your license key status — no usage tracking, no analytics, no telemetry.

---

## 🐛 Bug Reports

Found a bug? Please [open an issue](https://github.com/JordanH22/aircast/issues/new) with:
- Your macOS/tvOS version
- Steps to reproduce
- Any error messages or screenshots

---

## 📋 Changelog

### v1.0.0
- Initial release
- macOS and Apple TV support
- Smart EPG with intelligent channel matching
- Dual playback engine (AVPlayer + VLC)
- HEVC hardware decoding
- HDR10/HLG support
- VOD streaming (Movies & Series)
- Stream diagnostics dashboard

---

<p align="center">
  <sub>Built with ❤️ in the UK</sub><br>
  <sub>© 2025 AirCast. All rights reserved.</sub><br>
  <sub>Source code is private. This repository is for distribution only.</sub>
</p>
