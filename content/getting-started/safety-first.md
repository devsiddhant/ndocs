---
title: Safety First
---

The internet is full of malware, spyware, and bad actors. Before you download anything, read this.

## Trust No One
Even "trusted" sources can be compromised. Always verify what you download.

### VirusTotal
**[VirusTotal](https://www.virustotal.com/)** is a free service that analyzes files and URLs for viruses, worms, trojans, and other kinds of malicious content.

#### How to use it
1.  **Do not run** the file you just downloaded.
2.  Go to **[VirusTotal.com](https://www.virustotal.com/)**.
3.  Upload the file (or paste the URL).
4.  **Analyze the results**:
    *   **0/70**: Clean.
    *   **1-3/70**: Likely a "false positive" (generic detection), especially for pirated/modded software (cracks often look like malware to antiviruses). *Proceed with caution*.
    *   **Red Flags**: If major vendors (Microsoft, Kaspersky, BitDefender, Malwarebytes) flag it, **DELETE IT**.

> [!WARNING]
> VirusTotal is not a silver bullet. Fully Unicoded/FUD (Fully Undetectable) malware exists. Use common sense. If a 2GB game is a 5MB `.exe` file, it is a virus.

## Common Sense Rules
1.  **Check Extensions**: Ensure `movie.mp4` is not `movie.mp4.exe`. Enable "File name extensions" in Windows Explorer View settings.
2.  **Official Sources**: Always try to download from the official GitHub, website, or F-Droid. Avoid "softonic", "cnet", or random download buttons.
3.  **Sandboxing**: If you are unsure, run the file in **[Windows Sandbox](https://learn.microsoft.com/en-us/windows/security/application-security/application-isolation/windows-sandbox/windows-sandbox-overview)** or a **Virtual Machine** first.
