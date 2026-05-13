---
title: FOSS Apps
---

A collection of the best Free and Open Source Software (FOSS) for Windows. Prioritizing privacy, performance, and transparency.

## Browsers

### [Firefox](https://www.mozilla.org/en-US/firefox/new/)
The only major browser not built on Chromium (Google's engine).
*   **Why use it**: It is the last line of defense against a Google-monopolized web. Highly customizable with `about:config`.
*   *Hardening*: See our **[Firefox Hardening Guide](/privacy-guides-101/firefox-hardening)** to make it bulletproof.

### [Brave](https://brave.com/)
Chromium-based browser with privacy out of the box.
*   **Why use it**: If you need Chrome compatibility (for specific web apps) but don't want Google's tracking. Built-in adblocker is excellent and faster than extensions.
*   *Note*: Disable "Brave Rewards" and crypto features for a cleaner experience.

### [LibreWolf](https://librewolf.net/)
A fork of Firefox that focuses on privacy, security and freedom.
*   **Why use it**: It comes pre-configured with the Arkenfox `user.js` and other privacy tweaks. It strips out all Mozilla telemetry. The "install and forget" private browser.

## Media Consumption

### [VLC Media Player](https://www.videolan.org/vlc/)
The cone that plays everything.
*   **Why use it**: It has its own codecs built-in, so you don't need to install codec packs. It handles corrupt files, incomplete downloads, and weird formats better than anything else.

### [MPV](https://mpv.io/)
The hacker's media player. No GUI, just keyboard shortcuts and config files.
*   **Why use it**: Highest quality video rendering (upscaling, color correction) via widely available scripts. Extremely lightweight.
*   *Frontend*: **[MPV.net](https://github.com/mpvnet-player/mpv.net)** gives you the power of MPV with a context menu and settings dialog for normal humans.

### [MusicBee](https://www.getmusicbee.com/)
The ultimate music manager and player.
*   **Why use it**: Handles libraries with 500,000+ tracks without lagging. Extensive tagging tools, audio conversion, and syncing support.
*   *Note*: Not Open Source, but Freeware and highly respected.

## Utilities

### [7-Zip](https://www.7-zip.org/)
The standard for file compression.
*   **Why use it**: Opens everything (`.rar`, `.zip`, `.tar`, `.iso`). Higher compression ratio than WinRAR. Free forever, no "trial period" popups.

### [BleachBit](https://www.bleachbit.org/)
System cleaner.
*   **Why use it**: Frees up disk space and guards your privacy. Handles cookies, cache, temporary files, and logs.
*   *Warning*: Be careful with "Free Disk Space" (overwrite) options on SSDs as it adds unnecessary wear.

### [Portmaster](https://safing.io/portmaster/)
Application Firewall.
*   **Why use it**: Visualize and control all internet traffic on your PC. Block specific apps from phoning home (e.g., block an offline game from connecting to the internet).

### [ShareX](https://getsharex.com/)
The swiss army knife of screenshots.
*   **Why use it**: Don't just take screenshots; annotate them, blur sensitive info, upload them to Imgur/Cloudflare automatically, or record GIFs. It automates your workflow.

### [LocalSend](https://localsend.org/)
AirDrop for everyone.
*   **Why use it**: Transfer files between Windows, Mac, Linux, Android, and iOS instantly over your local WiFi. No data leaves your room. No servers involved.

### [PowerToys](https://github.com/microsoft/PowerToys)
System utilities by Microsoft.
*   **Features**:
    *   **FancyZones**: Create custom window layouts for easy multitasking.
    *   **PowerRename**: Bulk rename files using Regex.
    *   **Color Picker**: `Win+Shift+C` to grab the Hex code of any pixel on screen.
    *   **Text Extractor**: Copy text from images anywhere on screen.

## Productivity / Office

### [LibreOffice](https://www.libreoffice.org/)
The FOSS alternative to Microsoft Office.
*   **Why use it**: Compatible with `.docx` and `.xlsx` files. No subscription fees. No cloud telemetry.

### [Obsidian](https://obsidian.md/)
A knowledge base that works on top of a local folder of plain text Markdown files.
> [!WARNING]
> **Obsidian is NOT Open Source.** It is proprietary freeware. However, it is included here because:
> 1.  It is "Local First" (your data maps to actual `.md` files on your disk, not a database).
> 2.  It has a massive plugin ecosystem (many of which *are* FOSS).
> 3.  It is the standard for "Second Brain" note-taking.

### [Joplin](https://joplinapp.org/)
The true FOSS alternative for note-taking.
*   **Why use it**: Fully open source. End-to-end encryption. Syncs via Nextcloud, Dropbox, or OneDrive. Good for standard notes (less focused on "linking" than Obsidian).
