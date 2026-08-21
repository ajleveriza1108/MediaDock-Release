# MediaDock Release

Public release/update metadata for **MediaDock**.

## Current development version

**R1.6.18 — Release-Repo Updater + Trial Build Candidate**

The R1.6.18 Windows candidate has been built and staged-smoke verified. It remains **development**, because installed update-cycle verification and hosted installer publication are still gated.

## Stable updater rule

Customer builds read only latest-stable.json.

The stable pointer must remain inactive until the exact installer:

- is built;
- passes installed runtime/trial verification;
- is uploaded as a MediaDock-Release GitHub Release asset;
- has an independently verified SHA-256.

latest-development.json is informational and never triggers customer auto-update.

This repository must remain free of private commercial source, trial-reset tools, key inventories, secrets, customer/device records, logs, cookies, runtime state, or build caches.