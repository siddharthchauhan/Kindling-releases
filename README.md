# Kindling — releases

Download page and update feed for **Kindling**, an AI data-analyst desktop app.

This repository holds release binaries only. It carries no source code; it exists so
the application's auto-updater has a publicly readable feed while the source repository
stays private.

## Download

Get the latest build from the [Releases page](../../releases/latest).

| Platform | File |
| --- | --- |
| macOS — Apple Silicon (M1–M4) | `Kindling-<version>-arm64.dmg` |
| macOS — Intel | `Kindling-<version>-x64.dmg` |
| Windows | `Kindling.Setup.<version>.x64.exe` |

macOS builds are signed with a Developer ID and notarized by Apple: open the DMG and
drag Kindling to Applications. On Windows, if SmartScreen appears, choose
**More info → Run anyway**.

## Updating

Kindling checks for updates on its own and installs them when you click Restart, so
after the first install you should not need this page again. The `.zip`, `.yml` and
`.blockmap` files in each release are what the updater reads — they are not meant to
be downloaded by hand.
