# Genova IPTV – The Universal Multiplatform IPTV Player

> ⚠️ **Early Development Stage**
>
> This project is currently in its early stages of development. While we're working hard to create a robust IPTV player,
> please note that:
> - Features may be incomplete or subject to change
> - The application may contain bugs
> - Documentation is being actively updated
> - API stability is not guaranteed
>
> We welcome feedback and contributions to help improve the project.

<div align="center">
  <img src="assets/genova-logo.svg" alt="Genova Logo" width="200"/>

[![Kotlin](https://img.shields.io/badge/Kotlin-2.1.0-blue.svg)](https://kotlinlang.org)
[![Compose Multiplatform](https://img.shields.io/badge/Compose%20Multiplatform-1.9.0-orange.svg)](https://github.com/JetBrains/compose-multiplatform)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**The free IPTV player for everyone**

</div>

---

## 🎬 What is Genova IPTV?

**Genova IPTV** is a next-generation IPTV player designed for everyone. Enjoy your favorite TV channels, shows, and VOD content on any device, with a beautiful and intuitive interface. Genova is completely **free to use**.

---

## 🌟 Key Features

### Core Functionality
- **Universal Compatibility**: Works with Xtream Codes, M3U/M3U8 playlists, and public IPTV sources
- **MVP Platforms**: Android and tvOS (Apple TV)
- **Future Platforms**: iOS, macOS, Windows, Linux, Android TV (coming in post-MVP iterations)
- **Live TV & EPG**: Browse channels with integrated Electronic Program Guide
- **VOD & Series**: Browse movies and TV series with category organization
- **Smart Search**: Real-time search across all content types
- **Provider Management**: Full CRUD operations with validation and testing
- **No IPTV Service**: Player only - you provide your own IPTV sources

### Platform-Specific Highlights (MVP)

- **Android**: Jetpack Compose (Material Design 3), Bottom Navigation, Chaintech player
- **tvOS**: SwiftUI with VLC player, TabBar navigation, dedicated Search module
- **Shared Core**: Kotlin Multiplatform (KMP) codebase for business logic and data layer

### Feature Organization

- **Navigation**: Platform-optimized navigation (BottomNav/NavigationRail/TabBar)
- **Category-Based Content**: Intelligent organization by categories for all content types
- **State Management**: Comprehensive ViewModel architecture with error handling
- **Modal Detail Views**: Bottom sheets (Android) and detail views (tvOS)
- **Video Player**: Fullscreen playback for Live TV, VOD, and Series

---

## 🚀 Getting Started

1. **Download Genova IPTV** for your platform (coming soon to all major app stores and direct download).
2. **Add Your IPTV Source**:
   - Go to Settings > Streams
   - Enter your Xtream Codes credentials or M3U/M3U8 playlist URL
   - Genova will automatically fetch and organize your channels
3. **Browse & Watch**:
   - Explore Live TV channels organized by categories
   - Browse VOD movies and TV series
   - Use search to find specific content
   - Enjoy fullscreen video playback

---

## 🧪 Beta Testing

We're actively looking for beta testers to help improve Genova IPTV!

### 📱 Join Beta Testing (Android)

- **[Join from Android Device](https://play.google.com/store/apps/details?id=com.genova.player)** - Open this link on your Android device
- **[Join from Web Browser](https://play.google.com/apps/testing/com.genova.player)** - Join from any device

> **How it works**: Click one of the links above → Accept the beta invitation → Install Genova IPTV from Google Play Store → Start testing!

### 💬 Share Your Feedback

- **🐛 Report Bugs**: [GitHub Issues](https://github.com/GenovaIPTV/genova-public/issues)
- **💡 Feature Requests & Discussions**: [Google Group](https://groups.google.com/u/1/g/genova-player)

---

## ❓ FAQ

**Q: Does Genova provide IPTV channels?**
> No. Genova is a player only. You must provide your own legal IPTV sources (Xtream, M3U, etc.).

**Q: Is Genova free?**
> Yes! Genova is completely free to use. All features are available without any cost.

**Q: Is my data private?**
> Yes. Your playlists and settings are stored locally on your device. We don't collect or transmit your data.

**Q: What platforms are supported?**
> Currently: Android and tvOS (Apple TV). Coming soon: iOS, macOS, Windows, Linux, Android TV.

**Q: Where can I get help?**
> Join our [Google Group](https://groups.google.com/u/1/g/genova-player) for questions, discussions, and community support.

---

## 🆘 Support & Contact

- **Community Forum**: [Google Group](https://groups.google.com/u/1/g/genova-player) - Join our beta testing community for discussions and support
- **Bug Reports**: [GitHub Issues](https://github.com/GenovaIPTV/genova-public/issues) - Report bugs and technical issues

---

<div align="center">
  Made with ❤️ by the Genova Team
</div>
