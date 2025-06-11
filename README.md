# Flud - Torrent Downloader

<p>The most advanced, feature-rich BitTorrent client for Android.</p>

[![Website](https://img.shields.io/badge/Official_Website-fludapp.com-blue)](https://fludapp.com/) 
[![Play Store](https://img.shields.io/badge/Flud_Free-Google_Play-green)](https://play.google.com/store/apps/details?id=com.delphicoder.flud) 
[![Flud+](https://img.shields.io/badge/Flud+_Pro-Get_AdFree-orange)](https://play.google.com/store/apps/details?id=com.delphicoder.flud.paid) 
[![Community](https://img.shields.io/badge/User_Forum-Join_Discussion-yellow)](https://fludapp.com/forum/)

## Overview

Flud is a simple, beautiful, and powerful BitTorrent client for Android that brings the full power of the BitTorrent protocol to your mobile device. With its intuitive Material Design interface and comprehensive feature set, Flud has become one of the most trusted torrent clients in the Android ecosystem.

## 🚀 Features

### Performance
- **No speed limits** on downloads/uploads
- **Multi-threaded downloading** for maximum efficiency
- **Optimized piece selection algorithms** for faster completion
- **Support for extremely large files** (>4GB)
- **Sequential downloading** support for media streaming
- **Bandwidth throttling** with customizable limits

### Control & Management
- **Selective file downloading** - Choose specific files from torrents
- **File/folder priority settings** - Set priority levels for optimal management
- **Move files during downloads** - Organize content on-the-fly
- **RSS feed support** with automatic downloading
- **Magnet link support** for quick torrent adding
- **Download scheduling** with WiFi-only options

### Advanced Protocol Support
- **DHT (Distributed Hash Table)** for decentralized peer discovery
- **PeX (Peer Exchange)** for efficient peer sharing
- **µTP (Micro Transport Protocol)** for reduced network congestion
- **UPnP & NAT-PMP support** for automatic port forwarding
- **UDP tracker protocol** for faster tracker communication
- **BitTorrent v2 protocol** support

### Security & Privacy
- **Protocol encryption support** (MSE/PE) for enhanced privacy
- **IP filtering capabilities** to block unwanted connections
- **Proxy support** for trackers and peers (HTTP/SOCKS5)
- **WiFi-only download option** to save mobile data
- **Local peer discovery** for LAN-based sharing

### User Experience
- **Material Design interface** with modern aesthetics
- **Dark theme support** for comfortable viewing
- **Real-time statistics** and progress tracking
- **Detailed torrent information** view
- **Search integration** with external search engines
- **Multiple language support**

## 🔧 Protocol Implementation

Flud implements modern BitTorrent protocols following official BEP (BitTorrent Enhancement Proposal) specifications:

### Core Protocol
- **BEP-3**: BitTorrent Protocol Specification
- **BEP-10**: Extension Protocol for enhanced functionality
- **BEP-23**: Tracker Returns Compact Peer Lists
- **BEP-52**: BitTorrent v2 protocol implementation

### Peer Discovery
- **BEP-5**: DHT Protocol for decentralized peer discovery
- **BEP-11**: Peer Exchange (PEX) for efficient peer sharing
- **BEP-14**: Local Peer Discovery for LAN networks
- **BEP-15**: UDP Tracker Protocol for reduced overhead

### Advanced Features
- **BEP-6**: Fast Extension for rapid piece exchange
- **BEP-8**: Message Stream Encryption for privacy
- **BEP-29**: µTorrent Transport Protocol implementation
- **BEP-40**: Canonical Peer Priority for optimal connections

## 🏗️ Architecture

### Core Components

#### Network Layer
- **TCP/UDP socket management** for dual-protocol support
- **Peer connection pooling** for efficient resource usage
- **Protocol message handling** with proper state management
- **Bandwidth throttling** with QoS implementation
- **Connection encryption** using MSE/PE protocols

#### Storage Engine
- **Piece-based file allocation** for efficient disk usage
- **Hash verification system** ensuring data integrity
- **Partial file management** with resume capability
- **Disk I/O optimization** for mobile storage constraints
- **External SD card support** with proper permissions

#### Protocol Stack
- **BitTorrent v1/v2 support** with backward compatibility
- **Extension protocol (BEP-10)** for enhanced features
- **Encryption layer (MSE/PE)** for privacy protection
- **UDP tracker protocol** for improved performance
- **DHT implementation** for trackerless torrents

#### User Interface
- **Material Design components** following Google guidelines
- **Real-time statistics display** with live updates
- **Download management interface** with intuitive controls
- **Settings configuration** with advanced options
- **Notification system** for download status updates

## 📋 System Requirements

- **Android Version**: 4.1 (API level 16) or higher
- **RAM**: Minimum 1GB recommended
- **Storage**: 50MB for app installation + space for downloads
- **Network**: WiFi or mobile data connection
- **Permissions**: Storage access for file management

## 🔧 Installation

### From Google Play Store
[<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="200">](https://play.google.com/store/apps/details?id=com.delphicoder.flud)

1. Click "**Install**" to download and install automatically
2. Launch the app and grant necessary permissions

### Manual Installation
1. Download the APK from trusted sources
2. Enable "Unknown Sources" in Android settings
3. Install the APK file
4. Launch and configure the application

## 📖 Quick Start Guide

### Adding Torrents
1. **Torrent Files**: Tap the "+" button and select a .torrent file
2. **Magnet Links**: Copy magnet links and they'll be detected automatically
3. **URLs**: Paste torrent URLs directly in the app

### Configuration
1. **Storage Location**: Set default download directory
2. **Network Settings**: Configure proxy, encryption, and port settings
3. **Bandwidth Limits**: Set upload/download speed limits
4. **WiFi Settings**: Enable WiFi-only downloading to save mobile data

### Managing Downloads
- **Selective Downloads**: Choose specific files before starting
- **Priority Settings**: Set high/normal/low priority for files
- **Pause/Resume**: Control downloads individually
- **Sequential Mode**: Enable for streaming media files

## 🛡️ Privacy & Security

Flud prioritizes user privacy and security:

- **No tracking or analytics** in the core application
- **Local data processing** - no cloud dependencies
- **Encryption support** for protocol-level privacy
- **Proxy support** for IP masking
- **No ads** in the paid version
- **Open source components** where applicable

## 🤝 Contributing

We welcome contributions from the community:

1. **Bug Reports**: Submit detailed bug reports with reproduction steps
2. **Feature Requests**: Suggest new features or improvements
3. **Translations**: Help translate the app into more languages
4. **Testing**: Participate in beta testing programs

## 📄 License

Flud uses various open-source libraries and components. Please refer to the in-app license information for detailed attribution.

## 🆘 Support*

- **Official Website**: [fludapp.com](https://fludapp.com/)
- **Email Support**: support@delphisoftwares.com
- **Help translate Flud in your language so others can enjoy it too! Join the translation project here**: https://delphisoftwares.oneskyapp.com/collaboration/

## 🏆 Awards & Recognition

- **Featured on XDA Developers** as a top Android torrent client
- **Recommended by Android enthusiasts** worldwide
- **High ratings** on Google Play Store
- **Trusted by millions** of users globally

## 📊 Statistics

- **Downloads**: Over 10 million installations
- **Rating**: 4.3+ stars on Google Play
- **Active Users**: Millions of monthly active users
- **Supported Languages**: 20+ languages

## ⚖️ Legal Notice

Flud is a BitTorrent client software. Users are responsible for ensuring their use of the software complies with local laws and regulations. The developers do not endorse or encourage the use of the software for illegal purposes.

---

**This repository is for information purpose only.*
