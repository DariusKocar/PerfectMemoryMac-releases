# PerfectMemoryMac-releases

Public distribution channel for **Perfect Memory for macOS**. This repo exists only so
[Sparkle](https://sparkle-project.org) clients can fetch updates without authentication
(the app's source repo is private).

It hosts:

- **`appcast.xml`** — the Sparkle update feed referenced by the app's `SUFeedURL`.
- **GitHub Releases** — each `vX.Y.Z` release carries the signed + notarized `.dmg`
  (first-time human installs) and `.zip` (the Sparkle update payload).

Everything here is produced by the release workflow in the private `PerfectMemoryMac`
repo. **Do not commit source code here.**
