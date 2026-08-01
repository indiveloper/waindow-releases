# Waindow

Waindow is a free, account-free native Mac utility for saved window workspaces,
off-screen window rescue, window-specific Markdown memos, long-page capture,
Linked Resize, Blackout Mode, Keep Awake, and optional local control through
Shortcuts, MCP, or CLI.

## Download

- [Download the latest Waindow ZIP](https://www.waindow.app/download/started/github)
- [Read the install guide](https://www.waindow.app/download)
- [Open the current binary release](https://github.com/indiveloper/waindow-releases/releases/latest)

No GitHub account or Waindow account is required.

### Install with Homebrew

```sh
brew install --cask indiveloper/tap/waindow
```

This is Waindow's verified third-party tap, not an official Homebrew cask.
[Inspect the tap and its pinned checksum](https://github.com/indiveloper/homebrew-tap)
before installing if you prefer.

## What it does

- Save named workspaces, preview every planned move, and restore them with undo.
- Rescue windows whose title bars became unreachable after a display change.
- Arrange and focus standard macOS windows.
- Resize neighboring windows together with Linked Resize.
- Attach searchable local Markdown memos to specific windows.
- Capture supported long browser or document pages as one tall PNG.
- Darken connected displays temporarily with Blackout Mode.
- Keep the Mac awake with display and timer choices.
- Show total CPU or memory activity in the menu-bar icon.
- Run bounded local actions from Shortcuts, compatible MCP clients, or CLI.

## Choose by the job

Waindow is intentionally not the deepest specialist in every category. These
comparisons show the missing features before you download:

- [Rectangle or Waindow](https://www.waindow.app/rectangle-alternative) —
  dedicated keyboard and drag-to-edge window snapping versus a broader toolkit.
- [Shottr or Waindow](https://www.waindow.app/shottr-vs-waindow) — dedicated
  screenshot annotation and OCR versus simple long-page capture beside work tools.
- [Amphetamine or Waindow](https://www.waindow.app/amphetamine-vs-waindow) —
  deep keep-awake automation versus a simpler manual session in the same toolkit.

Choose the specialist when its deeper workflow is the main job.

## Requirements

- macOS 13.1 or later
- Apple Silicon or Intel Mac
- Current release: Waindow 1.5.0
- ZIP size: 5.83 MB (5,830,493 bytes)
- SHA-256: `b84688fa98951bd1c117122c682b7c81f25c0a9b0e40ca2c9a993ae05002d612`

## First launch

The current direct-download build uses a stable local signing identity and is
not Developer ID notarized. macOS may require explicit approval for a
downloaded build:

1. Move `Waindow.app` to Applications and try to open it.
2. If macOS blocks it, open **System Settings → Privacy & Security**.
3. Find the Waindow message, choose **Open Anyway**, authenticate if asked,
   and confirm **Open**.

Never disable Gatekeeper.

## Privacy and product boundary

Waindow has no account, payment, subscription, trial, product key, usage limit,
advertising, or app telemetry. It does not include an AI model, voice input,
AI-session monitoring, terminal monitoring, or work-progress alerts. Memos and
preferences stay local on the Mac.

This is a distribution-only repository. It contains release documentation and
the current compiled release asset; application and website source code are
not included or licensed as open source.

## Help and feedback

- [Product website](https://www.waindow.app/)
- [Verified product facts](https://www.waindow.app/about)
- [Verified product updates](https://www.waindow.app/updates)
- [Product updates RSS](https://www.waindow.app/updates/feed.xml)
- [Public feedback](https://github.com/indiveloper/waindow-releases/discussions/1)
- [Report a reproducible issue](https://github.com/indiveloper/waindow-releases/issues/new)

Do not include private memo text, credentials, company information, or
screenshots containing personal data in a public issue or discussion.
