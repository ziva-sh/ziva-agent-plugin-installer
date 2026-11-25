# Ziva installer

This repository hosts the compiled releases of the Ziva installer, the desktop app that installs Ziva into a Godot project. It contains no source code. Ziva is an AI agent that runs inside the Godot editor, made by Zivash Inc. (https://ziva.sh).

## What the installer does

- Lets you pick an existing Godot project or create a new one in an empty folder.
- Downloads the latest Ziva plugin from https://github.com/ziva-sh/ziva-agent-plugin-godot/releases and, if needed, Godot.
- Opens the project in Godot with the Ziva panel.
- Does not upload your project source files.

## Run it

Close your project in Godot first.

- macOS: download the installer from https://ziva.sh/download and open it.
- Windows, in PowerShell:

  ```powershell
  irm https://ziva.sh/install.ps1 | iex
  ```

- Linux:

  ```bash
  curl -fsSL https://ziva.sh/install.sh | bash
  ```

These downloads come from this repository's latest release, which has builds for Windows, macOS and Linux on x64 and ARM64: https://github.com/ziva-sh/ziva-agent-plugin-installer/releases/latest

Installing needs no account or paid plan. Full guide, including the manual zip install: https://ziva.sh/docs/installation

## What it installs

Ziva works in the Godot editor. It reads your project files, inspects the scene tree, checks editor errors, edits scenes and scripts, runs the game to check its work and fixes the errors it finds.

- Requirements: Godot 4.2 or later; Windows, macOS 13 or newer, or Linux; an internet connection for AI features.
- Plans: Hobby is free, Basic is $20/month, Pro is $50/month and Ultra is $200/month. Parallel mode and the Playtest Agent are on Pro and Ultra, in Godot only; Parallel mode uses much more plan usage than a normal chat. Details: https://ziva.sh/pricing
- Full feature list: https://github.com/ziva-sh/ziva-agent-plugin-godot#readme
- Documentation: https://ziva.sh/docs

## License

The installer and Ziva are proprietary software of Zivash, Inc. and are not open source; use is governed by the terms of service at https://ziva.sh/terms. This repository has no license file.

## Support

- Bug reports: https://github.com/ziva-sh/ziva-agent-plugin-godot/issues
- Discord: https://ziva.sh/discord
- Email: hello@ziva.sh
