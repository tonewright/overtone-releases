# Overtone and Timbre — beta releases

Overtone draws mods in Wuthering Waves on DirectX 12. Timbre is its mod manager: it installs your mods, keeps
Overtone current and starts the game with it.

This repository holds the beta's releases only. The source code will be published when Overtone leaves beta.

## Install

1. Download `Timbre_<version>_x64-setup.exe` from the [latest Timbre release](../../releases?q=timbre&expanded=true).
2. Run it. It installs for your Windows user alone and needs no administrator.
3. Open Timbre and follow its first setup.

Timbre fetches Overtone itself and keeps both current: when a newer Timbre is ready, an **Update** button appears
in its top bar.

These builds are not yet signed. Windows may say it protected your PC on the first run: choose **More info**, then
**Run anyway**. On a PC with Smart App Control on, the game cannot load Overtone until the builds are signed.

## Without Timbre

- **Overtone**: the `runtime-v…` releases hold the runtime's files.
- **MCP server**: `overtone-mcp.exe` in the `mcp-v…` releases connects an AI client to your mods.

## Versions

Each product has its own version: the day it was released and how many came before it that day (`26.1013.0`).
Every release carries `index.toml`, signed, which lists every release and which versions work together. Timbre reads
it to choose the runtime that matches it.

## Terms

The builds are under the beta terms in each release's `TERMS.txt`: free to use, not to redistribute. Each release's
`NOTICES.txt` lists the third-party components it includes and their licences.

## Problems

Open an issue here with what you did, what happened, and Timbre's diagnostics bundle (Settings → Diagnostics).
