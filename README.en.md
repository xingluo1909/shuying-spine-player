<div align="center">
  <br />
  <h1>Spine Player</h1>
  <p>
    <strong>Cross-platform Unofficial 2D Skeletal Animation Player</strong>
    <br />
    Multi-version Playback · Format Conversion · Skeleton Merge · Live2D · 3D Preview · AI Upscale
  </p>
  <p>
    <a href="#"><img src="https://img.shields.io/badge/Version-1.627.0-7c6af7?style=for-the-badge&labelColor=1a1a2e" alt="Version"></a>
    <a href="#"><img src="https://img.shields.io/badge/Spine-2.1%20%7C%203.x%20%7C%204.x-00d4aa?style=for-the-badge&labelColor=1a1a2e" alt="Spine"></a>
    <a href="#"><img src="https://img.shields.io/badge/Live2D-Cubism%202%20%7C%204-ff6b9d?style=for-the-badge&labelColor=1a1a2e" alt="Live2D"></a>
    <a href="#"><img src="https://img.shields.io/badge/MultiLang-中%20%7C%20EN%20%7C%20JP-4fc3f7?style=for-the-badge&labelColor=1a1a2e" alt="MultiLang"></a>
    <br />
    <a href="#"><img src="https://img.shields.io/badge/Tauri-ffc131?style=for-the-badge&labelColor=1a1a2e&logo=tauri" alt="Tauri"></a>
    <a href="#"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&labelColor=1a1a2e&logo=react" alt="React"></a>
    <a href="#"><img src="https://img.shields.io/badge/Rust-ed672f?style=for-the-badge&labelColor=1a1a2e&logo=rust" alt="Rust"></a>
    <a href="#"><img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&labelColor=1a1a2e&logo=three.js" alt="Three.js"></a>
    <a href="#"><img src="https://img.shields.io/badge/Pixi.js-B537B4?style=for-the-badge&labelColor=1a1a2e&logo=pixi.js" alt="Pixi.js"></a>
    <a href="#"><img src="https://img.shields.io/github/downloads/xingluo1909/shuying-spine-player/total?style=for-the-badge&labelColor=1a1a2e&color=brightgreen" alt="Downloads"></a>
  </p>
  <br />
</div>

<p align="center">
  🌐 <a href="README.md">中文</a> · <a href="README.en.md">English</a> · <a href="README.jp.md">日本語</a>
</p>

---

## 📖 Introduction

An **unofficial** cross-platform skeletal animation player integrating **playback, format conversion, skeleton merging, AI upscaling**, and more. Supports macOS (D-01-release only) and Windows. Currently features multi-version compatible playback from **Spine 2.1** to **3.x** to **4.x**, along with Live2D Cubism 2/4 and Unity FBX 3D model import.

<p align="center">
  <img src="IMG/MAIN.png" alt="Screenshot 1" width="800" />
</p>
  
## ✨ Features

### 🎬 Core Player
| Feature | Description |
|---------|------------|
| **Multi-version Spine** | 2.1 / 3.x / 4.x |
| **Multi-version Live2D** | Cubism 2 / 4 |
| **Dual Engine Rendering** | Enhanced (unified conversion) / Native (dual player core) |
| **Multi-layer Overlay** | Multiple Spine/Live2D files on screen simultaneously, independent scaling & drag reordering |
| **Animation Controls** | Play/Pause/Stop, frame-accurate seeking, loop mode switching |
| **Skin / Part Switching** | Real-time character skin switching, show/hide parts |
| **Export Module** | Single-frame PNG export, multiple resolution presets, AI upscale enhanced export |

---

## 🛠️ Tech Stack
| Layer | Technology |
|------|-----------|
| **Desktop Framework** | [Tauri 2](https://v2.tauri.app/) (Rust + WebView2) |
| **Frontend Framework** | [React 19](https://react.dev/) + TypeScript |
| **Backend Language** | Rust |

---

## 🗺️ Changelog

### D-02
1. Multi-language support (Chinese/English/Japanese), instant switch.

2. Live2D support with optimized player components for Spine + L2D same-screen playback:

<p align="center">
  <img src="IMG/L2D+.png" alt="Live2D Screenshot" width="800" />
</p>

3. FBX support:

<p align="center">
  <img src="IMG/FBX-FGO.png" alt="FBX Screenshot" width="800" />
</p>

4. Export functionality support.

### D-01
Spine version support. Merge module limited to 3.8 with same-source material.

| Source ↓ \ Target → | **3.8** | **4.0** | **4.1** | **4.2** |
|:-------------------:|:-------:|:-------:|:-------:|:-------:|
| **2.1** | ✅ | ✅ | ✅ | ✅ |
| **3.6** | ✅ | ✅ | ✅ | ✅ |
| **3.7** | ✅ | ✅ | ✅ | ✅ |
| **3.8** | ✅ | ✅ | ✅ | ✅ |
| **4.0** | ✅ | ✅ | ✅ | ✅ |
| **4.1** | ✅ | ✅ | ✅ | ✅ |
| **4.2** | ✅ | ✅ | ✅ | ✅ |

---

## 🔄 Roadmap
  Modules currently being tested:
- [ ] 1. Export module — more feature testing.
- [ ] 2. Pet mode testing.
- [ ] 3. Multi-theme testing.

---

> If you encounter any read errors, failures, or bugs, feel free to submit an Issue (preferably with files attached).  
> Project URL: https://github.com/xingluo1909/shuying-spine-player

---

> After D-02, most core features are complete. Due to real-world work commitments, maintenance is expected to be suspended indefinitely. Thank you for your support.
