# Perfect Memory for Mac

Perfect Memory remembers what you've seen on your screen and heard in meetings, keeps it on your
own Mac, and lets you, Claude or ChatGPT search it.

**[Download Perfect Memory](https://www.perfectmemory.ai/download?utm_source=github&utm_medium=readme&utm_campaign=mac-releases)** ·
[Website](https://www.perfectmemory.ai?utm_source=github&utm_medium=readme&utm_campaign=mac-releases) ·
[Connect Claude or ChatGPT](https://www.perfectmemory.ai/mcp?utm_source=github&utm_medium=readme&utm_campaign=mac-releases) ·
[Support](https://www.perfectmemory.ai/support?utm_source=github&utm_medium=readme&utm_campaign=mac-releases)

- **Search what you've seen.** It reads the text on your screen with Apple's on-device OCR, so
  you can find a page, a message or a number again. Press ⌥Space from any app to search.
- **Meeting notes with no bot in the call.** Zoom, Google Meet, Teams, Slack, Webex, WhatsApp
  and FaceTime calls are transcribed on your Mac, then summarized with action items.
- **Stays on your Mac.** Screenshots are encrypted with AES-256. Recording pauses in private
  browser windows, and you can exclude any app.
- **Works with your AI.** Claude, ChatGPT, Cursor and other MCP clients can search your memory.
  MCP calls are unlimited on every plan, including Free.

Free to use. Pro is $15 a month billed yearly, or $79 once if you bring your own AI (Ollama,
LM Studio or an API key).

Requires an Apple silicon Mac with macOS 14 or later. Also available
[for Windows](https://www.perfectmemory.ai/download?utm_source=github&utm_medium=readme&utm_campaign=mac-releases).

## About this repository

This repo is the public distribution channel for the Mac app. It exists only so
[Sparkle](https://sparkle-project.org) clients can fetch updates without authentication
(the app's source repo is private).

It hosts:

- **`appcast.xml`** — the Sparkle update feed referenced by the app's `SUFeedURL`.
- **GitHub Releases** — each `vX.Y.Z` release carries the signed + notarized `.dmg`
  (first-time human installs) and `.zip` (the Sparkle update payload).

Everything here is produced by the release scripts in the private `PerfectMemoryMac`
repo. **Do not commit source code here.**
