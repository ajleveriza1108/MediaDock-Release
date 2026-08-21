# MediaDock Release

Public release/update metadata for **MediaDock**.

## Current development version

**R1.6.19 — Dual-Mode Updater + Trial Build Candidate**

R1.6.19 supports both installed and portable update artifacts.

The stable updater pointer remains inactive until the exact installer and portable ZIP are hosted and the Windows update cycle is verified.

## Stable updater schema v2

Customer builds read only latest-stable.json.

The stable manifest contains both:
- installerUrl / installerSha256
- portableUrl / portableSha256

Installed copies select the installer.
Portable copies select the portable ZIP.

latest-development.json is informational only and cannot trigger customer auto-update.

This repository must remain free of private commercial source, developer reset tools, keys, secrets, customer/device data, runtime state, logs, cookies, and build caches.