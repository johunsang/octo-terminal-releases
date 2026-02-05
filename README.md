<p align="center">
  <img src="images/app_icon.png" alt="Octo Terminal" width="128" height="128">
</p>

<h1 align="center">🐙 Octo Terminal</h1>

<p align="center">
  <strong>A tiny, cute, and powerful Rust-based terminal for AI coding assistants</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-Rust-orange?logo=rust" alt="Rust">
  <img src="https://img.shields.io/badge/Framework-Tauri%202.0-blue?logo=tauri" alt="Tauri">
  <img src="https://img.shields.io/badge/Frontend-React%2018-61dafb?logo=react" alt="React">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey" alt="Platform">
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#download">Download</a> •
  <a href="#usage">Usage</a> •
  <a href="#roadmap">Roadmap</a>
</p>

<p align="center">
  <img width="1139" alt="Octo Terminal Screenshot" src="https://github.com/user-attachments/assets/ae228fa6-0dc3-4bad-8c58-7bebea2f6eb5" />
</p>

---

## ✨ Why Octo Terminal?

**Octo Terminal** is a lightweight, Rust-powered terminal application designed specifically for developers who work with AI coding assistants. Built with Tauri 2.0, it delivers native performance in a tiny package (~15MB) while providing a beautiful, modern interface.

### 🦀 Rust at its Core

- **Blazing Fast**: Native Rust backend for PTY management
- **Memory Efficient**: Minimal resource footprint (~15MB)
- **Cross-Platform**: Single codebase for macOS and Windows
- **Secure**: Rust's memory safety guarantees

---

## 🚀 Features

### 🤖 AI Assistant Integration

Seamlessly work with multiple AI coding assistants:

| Assistant | Launch | Modes |
|-----------|--------|-------|
| **Claude Code** | 🟠 One-click | Normal, Auto-accept, Bypass |
| **Codex CLI** | 🟢 One-click | Normal, Auto-edit, Full-auto |

- **Preset Prompts**: Save and reuse your favorite prompts
- **Slash Commands**: Quick access to `/help`, `/clear`, `/compact`, etc.
- **Auto-accept Mode**: Let AI work autonomously

### 📺 Multi-Terminal Workspace

Run multiple terminals simultaneously in a single window:

```
┌─────────────────────────────────────────┐
│  Project A (Claude)  │  Project B (Shell) │
├─────────────────────┼────────────────────┤
│  $ claude           │  $ npm run dev     │
│  > Working on...    │  Server running... │
├─────────────────────┼────────────────────┤
│  Project A (Shell)  │  Project C (Codex)  │
│  $ git status       │  $ codex --full    │
│  On branch main     │  > Analyzing...    │
└─────────────────────┴────────────────────┘
```

- **Layout Modes**: Tabs, Grid (2x2, 3x3, etc.), or Mix
- **Per-Project Themes**: Each project gets its own color scheme
- **Independent Sessions**: Each terminal runs in its own PTY

### 📁 Multi-Project Management

- **Project Tabs**: Quick navigation between projects
- **100+ Project Icons**: Visually distinguish your projects
- **Recent Projects**: Instant access to recently opened folders
- **Per-Project Settings**: Theme, font, and layout per project

### ✏️ Built-in Code Editor

- **File Tree**: Navigate your project structure
- **Auto-save**: Never lose your work (3-second interval)
- **Quick Edits**: Simple editor for fast modifications

### 🎨 Customization

**50+ Themes**: Mocha, Dracula, Nord, Tokyo Night, Gruvbox, Solarized, One Dark, Material, and more

**Fonts**: Fira Code, JetBrains Mono, SF Mono, Menlo, Consolas, Monaco

### ⚡ Productivity Features

- **Quick Commands**: Save frequently used commands
- **SSH Connections**: Store and quick-connect to servers
- **Git Presets**: Common git commands one click away
- **Keyboard Shortcuts**: Vim-inspired, fully customizable

---

## 📥 Download

Get the latest version from [Releases](https://github.com/johunsang/octo-terminal-releases/releases):

| Platform | Architecture | Download |
|----------|--------------|----------|
| macOS | Apple Silicon (M1/M2/M3) | `Octo.Terminal_x.x.x_aarch64.dmg` |
| macOS | Intel | `Octo.Terminal_x.x.x_x64.dmg` |
| Windows | x64 | `Octo.Terminal_x.x.x_x64.msi` |

### macOS Installation

1. Download the DMG file
2. Open the DMG
3. Drag `Octo Terminal.app` to Applications folder

> ⚠️ **If Gatekeeper warning appears:**
> - Go to **System Preferences** → **Security & Privacy** → Click **"Open Anyway"**

### Windows Installation

1. Download the MSI file
2. Run the installer
3. Follow the installation wizard

---

## 🎯 Usage

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Cmd/Ctrl + T` | New Terminal |
| `Cmd/Ctrl + W` | Close Terminal |
| `Cmd/Ctrl + ]` | Next Terminal |
| `Cmd/Ctrl + [` | Previous Terminal |
| `Cmd/Ctrl + N` | New Project |
| `Cmd/Ctrl + ,` | Settings |
| `Cmd/Ctrl + 1-9` | Switch Terminal |

### Terminal Input

| Shortcut | Action |
|----------|--------|
| `Ctrl + A` | Go to line start |
| `Ctrl + E` | Go to line end |
| `Ctrl + U` | Delete to start |
| `Ctrl + K` | Delete to end |
| `↑ / ↓` | Command history |

---

## 🔧 System Requirements

| OS | Minimum Version |
|----|-----------------|
| macOS | 10.15 (Catalina) or later |
| Windows | Windows 10 or later |

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend** | Rust, Tauri 2.0, portable-pty |
| **Frontend** | React 18, TypeScript, Vite |
| **Terminal** | xterm.js, WebGL addon, Unicode11 |
| **Styling** | CSS Variables, Custom themes |

---

## 🔮 Roadmap

- [ ] **Multi-Agent Support**: Run multiple AI agents collaboratively
- [ ] **Image Generation**: AI-powered image editing integration
- [ ] **Collaborative Editing**: Real-time co-editing support
- [ ] **Plugin System**: Extend functionality with plugins
- [ ] **Linux Support**: Native Linux builds
- [ ] **Cloud Sync**: Sync settings across devices

---

## 🐛 Bug Reports

If you encounter any issues, please report them in [Issues](https://github.com/johunsang/octo-terminal-releases/issues).

---

## 📄 License

MIT License - Copyright © 2024-2025 Octo Terminal

*This repository contains release binaries only. Source code is not included.*

---

<p align="center">
  <strong>🐙 Octo Terminal</strong><br>
  <em>Small. Cute. Powerful.</em><br><br>
  Built with 🦀 Rust & ❤️ by <a href="https://github.com/johunsang">johunsang</a>
</p>
