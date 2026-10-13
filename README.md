# Overtone and Timbre — beta releases

Overtone is a mod loader for Wuthering Waves on DirectX 12. Timbre is its mod manager.

This repository hosts beta builds only. Source code will be published at 1.0.

**Download and guides: [ivanlisovyi.github.io/overtone-releases](https://ivanlisovyi.github.io/overtone-releases/)**

## Install

1. Download `Timbre_<version>_x64-setup.exe` from the [latest Timbre release](../../releases?q=timbre&expanded=true).
2. Run it. Per-user install, no administrator rights.
3. Complete Timbre's first setup.

Timbre downloads Overtone and keeps both up to date.

Builds are unsigned. At the SmartScreen prompt, choose **More info**, then **Run anyway**. With Smart App Control on,
the game cannot load Overtone until builds are signed.

## Releases

| Tag | Contents |
| :--- | :--- |
| `timbre-v…` | Timbre installer |
| `runtime-v…` | Overtone runtime |
| `mcp-v…` | `overtone-mcp.exe`, an MCP server for AI clients |

Versions are `YY.MMDD.N`. Each release includes a signed `index.toml` listing every release and which versions work
together.

## Terms

Free to use, not for redistribution: see `TERMS.txt` in each release. Third-party licences are in `NOTICES.txt`.

## Issues

Open an issue with the steps to reproduce and Timbre's diagnostics archive (Settings → Diagnostics).
