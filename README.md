
<div align="center">
<img src="/assets/logo.png" height="150" />
</div>

<h1 align="center">PlanSolve</h1>

<p align="center">Solve routing, task-assignment, and shift-scheduling problems without leaving your terminal.</p>

<div align="center">
<img src="/assets/screenshot.png" height="400" />
</div>

## ⬇️ **Installation**

The `plansolve` CLI is a single self-contained binary — no runtime and no Rust toolchain required. Every command below installs the latest release automatically.

### macOS / Linux (shell)

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/plansolve/distro/releases/latest/download/plansolve-cli-installer.sh | sh
```

### Windows (PowerShell)

```powershell
powershell -ExecutionPolicy Bypass -c "irm https://github.com/plansolve/distro/releases/latest/download/plansolve-cli-installer.ps1 | iex"
```

### Homebrew (macOS)

```sh
brew tap plansolve/tap
brew install plansolve
```

### Scoop (Windows)

```powershell
scoop bucket add plansolve https://github.com/plansolve/distro
scoop install plansolve
```

### Cargo

```sh
cargo binstall plansolve-cli   # downloads the prebuilt binary
cargo install plansolve-cli    # builds from source
```

### Direct download

Grab a binary for your platform from the [latest release](https://github.com/plansolve/distro/releases/latest).

## 🚀 **Quickstart**

```sh
export PLANSOLVE_API_KEY=your-key
plansolve solve field-service request.json
```

## 📝 **License**

This project is proprietary software. All rights reserved.

## 🤝 **Support**

For support and questions, please contact the development team.
