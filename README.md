<p align="center">
  <img src="assets/hyperox.png" alt="HyperOx" width="120">
</p>

<h1 align="center">HyperOx runtime</h1>

<p align="center">
  <b>HyperOx in your terminal.</b><br>
  A terminal workspace for AI coding agents: tabs, panes and agent status, right inside the shell you already use.
</p>

<p align="center">
  <a href="https://github.com/buckleson/h0x-ADE-Releases"><b>HyperOx app</b></a> ·
  <a href="https://www.pavii.tech/products/dev-tools/docs/"><b>Documentation</b></a> ·
  <a href="https://pavii.tech"><b>Pavii</b></a> ·
  <a href="https://buckleson.com"><b>Buckleson</b></a> ·
  <a href="https://github.com/buckleson/h0x-ADE-Runtime-Releases/releases"><b>All releases</b></a>
</p>

---

## What is this?

The runtime (`h0x`) is the terminal version of HyperOx. Run it in any terminal to get tabs, split panes and a live status for every agent. This page holds the signed runtime files and the release notes for each version.

## Files in each release

| File | For |
|---|---|
| `h0x-windows-x86_64.zip` | Windows (x86-64) |
| `h0x-macos-aarch64` | macOS (Apple Silicon) |
| `h0x-macos-x86_64` | macOS (Intel) |
| `h0x-linux-x86_64` | Linux (x86-64) |
| `h0x-linux-aarch64` | Linux (ARM64) |
| `install.ps1`, `install.sh`, `install.cmd` | Installers |
| `latest.json` | Version information read by the updater |
| `agent-detection.toml` and agent files | How the runtime recognises each coding agent |

Every file comes with a `.minisig` signature, and the updater checks it before installing.

## Updates

The runtime keeps itself up to date automatically. If an update fails, it goes back to the version that worked.

## License

Apache License 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
