---
title: Microsoft Apps + Windows Management
---

Windows 10 and 11 come filled with "Bloatware" (pre-installed junk), telemetry (tracking), and ads. These tools help you reclaim your PC.

## Debloating & Privacy

### [Chris Titus Tech's WinUtil](https://github.com/ChrisTitusTech/winutil)
The ultimate Windows utility.
*   **What it does**:
    *   **Debloat**: Removes Candy Crush, Cortana, and other pre-installed trash.
    *   **Tweaks**: Enhances privacy, stops updates from rebooting your PC, and cleans up temporary files.
    *   **Install**: A built-in package manager to install your favorite apps (Firefox, Discord, etc.) in one click.
*   *Usage*: Run this in PowerShell (Admin):
    ```powershell
    irm christitus.com/win | iex
    ```

### [O&O ShutUp10++](https://www.oo-software.com/en/shutup10)
A free antispy tool.
*   **Why use it**: Windows settings are confusing and spread out. O&O gathers all privacy related settings (Location, Telemetry, Advertising ID) into one simple list.
*   *Tip*: Use the "Recommended Settings" action to apply safe privacy tweaks without breaking system functionality.

## Activation
> [!CAUTION]
> Discussion of activation tools is for educational purposes. We recommend supporting developers if you can afford it.

### [MassGravel (MAS)](https://github.com/massgravel/Microsoft-Activation-Scripts)
The most trusted open-source Windows and Office activator.
*   **Why use it**:
    *   **Open Source**: The code is transparent on GitHub. No hidden malware.
    *   **HWID**: Uses "Hardware ID" activation. This is a *permanent* activation that survives system wipes and reinstalls. It looks like a genuine digital license to Microsoft.
*   *Usage*: Run in PowerShell (Admin):
    ```powershell
    irm https://massgrave.dev/get | iex
    ```

## Package Managers

### [Winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/)
Microsoft's official package manager.
*   **About**: It's like an App Store for the command line.
*   **Usage**: `winget search firefox` -> `winget install Mozilla.Firefox`.
*   *Graphical Interface*: Try **[WingetUI](https://github.com/marticliment/WingetUI)** if you prefer a GUI.

### [Scoop](https://scoop.sh/)
A command-line installer for developers.
*   **Why use it**: It installs programs into your user folder (`C:\Users\You\scoop`). This keeps your system clean. No UAC popups, no pollution of `C:\Program Files`. Essential for dev tools (Node, Python, Git).
