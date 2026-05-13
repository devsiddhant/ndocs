---
title: FOSS Apps
---

Free and open-source software (**FOSS**) is software available under a license that grants users the right to use, modify, and distribute the software. This transparency normally leads to better privacy and security.

### How to install FOSS apps?
Most of these apps are available on **[F-Droid](https://f-droid.org/)**, an app store for FOSS applications. You can also get them from GitHub directly.
See the **[Droid-ify](#droid-ify)** section below for a better F-Droid client.

---

### [Canta](https://github.com/samolego/Canta)
An uninstall tool to debloat your Android device without root.
*   **The Problem**: Phones come with Facebook, Netflix, and Carrier apps installed as "System Apps" that you can't uninstall.
*   **The Solution**: Canta uses Shizuku (ADB) to forcibly uninstall these packages for the current user.

### [Voice Audiobook Player](https://github.com/PaulWoitaschek/Voice)
A minimal, material design audiobook player.
*   **Why use it**: Simple folder-based library. It remembers exactly where you left off. No subscriptions, just plays your local `.mp3` or `.m4b` files perfectly.

### [Fossify Tools](https://github.com/FossifyOrg)
The new standard for basic mobile tools (Gallery, Phone, Contacts, Calculator, Clock).
*   **Context**: These are forks of the popular "Simple Mobile Tools". The original developer sold the apps to ZipoApps (an adware company), and they are now filled with subscriptions and ads.
*   **Why use it**: Fossify is the original, clean, open-source code maintained by the community. **Do not download "Simple Gallery" from the Play Store anymore.**

### [LabNex](https://github.com/labnex/labnex)
A native Android client for GitLab.
*   **Why use it**: The web interface for GitLab on mobile is clunky. LabNex provides a smooth native experience for managing your code, reviewing merge requests, and checking CI/CD pipelines.

### [Lawnchair](https://lawnchair.app/)
A home screen replacement based on the Pixel Launcher.
*   **Why use it**: It gives you the "Google Pixel" look and feel on any phone (Samsung, Xiaomi, etc.).
*   **Features**: It has the "At a Glance" widget and supports Google Discover (with a plugin), but adds heavy customization options like icon packs, hiding apps, and gesture controls.

### [RethinkDNS](https://rethinkdns.com/)
A local DNS resolver and firewall.
*   **Firewall**: Android (surprisingly) has no built-in way to block an app from accessing the internet. RethinkDNS allows you to block internet access for specific apps (e.g., block a single-player game from showing ads or an offline calculator from tracking you).
*   **DNS**: It can encrypt your DNS queries (DoH/DoT) to hide your browsing history from your ISP.

### [Droid-ify](https://github.com/Droid-ify/Droid-ify)
A modern client for F-Droid.
*   **The Problem**: The official F-Droid app is old, slow, and clunky.
*   **The Solution**: Droid-ify looks like the Play Store (Material You). It updates repositories faster and installs apps more reliably.

### [VLC for Android](https://videolan.org/vlc/)
The definitive media player.
*   **Why use it**: Plays everything. Network stream support means you can stream videos from your PC (SMB/FTP) to your phone easily.

### [QUIK SMS](https://github.com/octoshrimpy/quik)
A lightweight SMS app.
*   **Why use it**: A database-free, telemetry-free SMS app. It does one thing and does it well.

### [Shizuku](https://shizuku.rikka.app/)
The magic tool for power users.
*   **What it is**: It allows regular apps to use system APIs (ADB rights) without root.
*   **How to use**: You enable "Wireless Debugging" in Developer Options, pair it with Shizuku, and start the service.
*   **Benefit**: Enables powerful apps like **Canta** (debloat), **SwiftBackup** (batch backup), and **Droid-ify** (seamless updates) to work without rooting your phone.

### [Obtainium](https://github.com/ImranR98/Obtainium)
Get app updates directly from the source.
*   **The Problem**: F-Droid builds happen on their server, so updates can be delayed by days or weeks.
*   **The Solution**: Obtainium checks the GitHub/GitLab "Releases" page of an app and downloads the APK directly from the developer as soon as it's out. Ideal for fast-updating apps.