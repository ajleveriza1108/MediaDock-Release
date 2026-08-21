# MediaDock Release Repository

Public release/update metadata for MediaDock.

## Current development version

R1.6.19 - Installer-Only Release Updater

Status: Windows installer candidate built and staged-smoke verified. Installed update-cycle verification and stable artifact publication remain gated.

## Customer update source

Installed customer builds read only:

https://raw.githubusercontent.com/ajleveriza1108/MediaDock-Release/main/latest-stable.json

latest-development.json is informational only.

## Distribution policy

Beginning with R1.6.19, MediaDock uses one customer artifact: the Windows installer EXE.

Stable installers belong in this repository's GitHub Releases assets. The stable manifest must remain inactive until the exact hosted installer passes runtime/update-cycle verification and its SHA-256 is confirmed.

This repository must remain free of private commercial source, reset utilities, key inventories, secrets, customer/device records, logs, cookies, runtime state, or build caches.