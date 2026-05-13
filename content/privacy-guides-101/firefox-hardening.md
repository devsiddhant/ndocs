---
title: Hardening Firefox
---

Firefox is the most private browser out of the box, but we can make it better. Much better.

## What is Hardening?
Hardening involves modifying the `user.js` file in your Firefox profile to override default settings. This disables telemetry, pocket, sponsored shortcuts, and strengthens fingerprinting resistance.

## The Easy Way: Librewolf
If you don't want to configure anything, download **[LibreWolf](https://librewolf.net/)**. It is a fork of Firefox with all of the below applied by default.

## The Manual Way: Arkenfox
**[Arkenfox](https://github.com/arkenfox/user.js)** is the community standard for a privacy-focused `user.js` template.

### Setup Guide
1.  **Download Firefox**: Install the standard release.
2.  **Locate Profile**: Go to `about:support` in the URL bar. Look for "Profile Folder" and click "Open Directory".
3.  **Create user.js**:
    *   Go to the [Arkenfox GitHub](https://github.com/arkenfox/user.js).
    *   Download the `user.js` file.
    *   Place it inside your Profile Folder.
4.  **Restart Firefox**: The settings will be applied automatically on search.

### Critical Extensions
Hardening is incomplete without extensions.
1.  **[uBlock Origin](https://addons.mozilla.org/firefox/addon/ublock-origin/)**: The only adblocker you need.
    *   *Tip*: Go to Settings > Filter lists > Enable everything under "Ads", "Privacy", "Malware domains", and "Annoyances".
2.  **[Skip Redirect](https://addons.mozilla.org/firefox/addon/skip-redirect/)**: Skips intermediary tracking pages.
3.  **[CanvasBlocker](https://addons.mozilla.org/firefox/addon/canvasblocker/)**: (Optional if using Arkenfox, as it has built-in resistance) Fakes canvas API readout preventing fingerprinting.

### about:config Tweaks
If you just want to toggle a few things without a full user.js:
*   `privacy.resistFingerprinting = true` (Warning: breaks some site layouts/timezones)
*   `network.dns.disablePrefetch = true`
*   `network.prefetch-next = false`
