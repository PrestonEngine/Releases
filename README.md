# PrestonEngine Downloads

Official Windows installers and portable packages for PrestonEngine.

## Download

Open [the latest stable release](https://github.com/PrestonEngine/Releases/releases/latest).

- **PrestonEngineSetup-&lt;version&gt;.exe** — Windows installer, Start Menu shortcut, optional desktop shortcut, and uninstaller.
- **PrestonEngine-&lt;version&gt;-Windows-x64.zip** — portable application.
- **SHA256SUMS.txt** — download checksums.
- **update.json** — versioned metadata used by the installed editor's update checker.

## Install

Choose **Install for all users** and approve the administrator prompt to install into Program Files.
Choose **Install for me only** to install into your user Programs folder without administrator permission.

Requires Windows 10 x64 version 1809 or newer, or Windows 11, and a DirectX 12 GPU supporting feature level 11_0.
Required SDL3 and Visual C++ runtime DLLs are included. The binaries are not code signed yet.

## Projects and updates

Projects normally live in Documents/PrestonEngine/Projects. Editor settings live in AppData/Roaming/PrestonEngine/Editor.
Reinstalling, updating, or uninstalling the application preserves those folders.

Use **File > Check for Updates** in installed versions with the update checker. Updates use the official full Windows installer and verify SHA-256 before installation.

This repository contains public release information and distribution artifacts only.
