# Waindow

Waindow is a native Mac utility for arranging windows, restoring workspaces,
keeping local Markdown memos, finishing long-page captures, copying visible
screen text, tidying the menu bar, presenting and recording product demos, and
running optional local actions through Shortcuts, MCP, or CLI.

Every feature is currently free to use. Waindow becomes a paid app on
**December 1, 2026** (future pricing and license terms have not yet been
announced). The current `1.12.0` build requires no account, product key, or
subscription.

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
- Arrange standard macOS windows into full-height columns or toggle to a balanced grid (`Control–Option–A`), plus halves, quarters, thirds, center, maximize, display moves, and restore.
- Browse open, minimized, and off-screen windows as album cards with Window Finder (`Control–Option–P`) and bring the chosen window to the center of the current display.
- Hold a window edge or corner for 1 second to resize neighboring windows together with Linked Resize and flowing neon outlines.
- Attach searchable local Markdown memos to specific windows (`Control–Option–N` / `Control–Option–Shift–N`); closing a window retains its notes with the app in the same unified editor.
- Capture supported long pages (`Control–Option–S`), then save, copy, pin, or extract text on device.
- Drag over visible text anywhere on screen (`Control–Option–Shift–S`) and copy it locally without saving a screenshot.
- Hide extra menu-bar icons behind a permission-free Waindow divider (`Control–Option–H`), drop a compact bar right below the MacBook camera notch (`Control–Option–Shift–H`, or automatically when expanding Tidy Menu Bar while icons remain behind the notch) to see and click notch-occluded icons without Screen Recording access, and search menu-bar items by name from the Quick Panel.
- Darken connected displays temporarily with Blackout Mode (`Control–Option–B`).
- Keep the Mac awake with display, timer, end-time, and direct-build closed-lid choices.
- Show whole-Mac CPU or memory activity in the four-tile menu-bar icon, and inspect live per-app CPU (≥ 1%) and memory (≥ 200 MB) usage while Mac Status is open.
- Open the complete menu with one menu-bar click, or double-click for shortcut-aware Quick Panel search.
- Point, spotlight, annotate, and restore a live presentation session without recording it.
- Record a display, app, window, or region into a recoverable local Studio project.
- Trim, split, reframe, enhance pointer movement, and export MP4 or short GIF files locally.
- Run bounded local actions from Shortcuts, compatible MCP clients, or CLI.

## Choose by the job

Waindow is intentionally not the deepest specialist in every category. These
comparisons show the missing features before you download:

- [Rectangle or Waindow](https://www.waindow.app/rectangle-alternative) —
  dedicated keyboard and drag-to-edge window snapping versus a broader toolkit.
- [Shottr or Waindow](https://www.waindow.app/shottr-vs-waindow) — deep
  screenshot editing versus focused long-page capture beside work tools.
- [Amphetamine or Waindow](https://www.waindow.app/amphetamine-vs-waindow) —
  deep keep-awake automation versus a simpler manual session in the same toolkit.

Choose the specialist when its deeper workflow is the main job.

## Independent public listing

Waindow appears in the
[Awesome Free Apps Window Management directory](https://github.com/Axorax/awesome-free-apps#window-management)
after its maintainer merged [PR #221](https://github.com/Axorax/awesome-free-apps/pull/221).
This is a directory listing, not a product review, rating, endorsement, or proof
of usage.

## Requirements

- macOS 13.1 or later
- Apple Silicon or Intel Mac
- Current release: Waindow 1.12.0 (130)
- ZIP size: 8.13 MB (8,127,116 bytes)
- SHA-256: `1c4f05bda3e483bd1878f53edb6c2bf039abc9fe1b30537eaa088aa3ba6bf18d`

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

Waindow is currently free to use and transitions to a paid app on December 1,
2026. The current `1.12.0` build has no account, payment, subscription, trial,
product key, usage limit, advertising, or app telemetry. It does not include an
AI model, voice transcription, AI-session monitoring, terminal monitoring, or
work-progress alerts. Memos and preferences stay local on the Mac. Hidden Menu
Bar Icons reuses the existing Accessibility permission only while its bar or
Quick Panel is open, reads no screen pixels (no Screen Recording permission),
discards item handles on close, and runs no idle background timer. Studio
records only the source and optional microphone or camera explicitly chosen for
that recording; projects and exports stay local. Screen Text runs only when
invoked, keeps the frozen frame in memory, and creates no screenshot file, OCR
history, telemetry, or network request. Mac Status reads local process names,
executable paths, CPU time, and memory footprints only while its panel is
visible, stops sampling and clears displayed process data when closed or hidden,
never reads command arguments or document contents, and stores no history.

This is a distribution-only repository. It contains release documentation and
the current compiled release asset; application and website source code are
not included or licensed as open source.

## Help and feedback

- [Product website](https://www.waindow.app/)
- [Verified product facts](https://www.waindow.app/about)
- [Verified product updates](https://www.waindow.app/updates)
- [Product updates RSS](https://www.waindow.app/updates/feed.xml)
- [Maker: indiveloper](https://github.com/indiveloper) · [@sornrus on X](https://x.com/sornrus)
- [Public feedback](https://github.com/indiveloper/waindow-releases/discussions/1)
- [Report a reproducible issue](https://github.com/indiveloper/waindow-releases/issues/new)

Do not include private memo text, credentials, company information, or
screenshots containing personal data in a public issue or discussion.
