# Quad Harness downloads

Download page and update files for **Quad Harness**, a local-first agent harness for macOS.

This repository holds only the finished app downloads. It contains no source code.

## Install

1. Open the [latest release](../../releases/latest) and download the `.dmg` (Apple Silicon Macs).
2. Open it and drag **Quad Harness** onto **Applications**.
3. The app is not signed with a developer identity or notarised, so macOS refuses it the first time:
   open it with right-click > **Open**, or run once
   `xattr -dr com.apple.quarantine "/Applications/Quad Harness.app"`.

## Updates

From version 0.1.1 the app updates itself: Settings > About checks this repository for a newer
release, shows what changed, and installs it only if it carries the publisher's signature.
Version 0.1.0 has no updater; install a newer one by hand once.
