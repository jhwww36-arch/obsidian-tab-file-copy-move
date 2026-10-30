# Obsidian tab file copy and move — Drag, Copy, Move & Import

Organize files directly from Obsidian's tab bar. Hold a modifier key, drag a tab onto a folder, and release to copy or move the file.

## Highlights

- **Copy and move vault files:** Alt-drag to copy; Ctrl-drag to move through Obsidian's native file manager, honoring automatic link-update preferences.
- **Import external files:** copy external Markdown files into your vault, or move them after the imported copy has been verified.
- **Scroll while dragging:** keep the mouse button and modifier held while using the wheel. Optional edge scrolling helps reach distant folders.
- **Record your shortcuts:** click Change, hold your preferred modifiers, and click Confirm. Copy and move shortcuts are independent.
- **Keep native tab behavior:** unmodified dragging continues to move, split, or dock tabs.
- **English throughout:** settings, notifications, drag hints, diagnostics, and errors are now in English.

## Installation

Requires **Obsidian desktop 1.14.4 or later**. Mobile is not supported.

1. Download `vault-file-drop-0.2.1.zip` below.
2. Extract its `vault-file-drop` folder into your vault's `.obsidian/plugins/` directory.
3. Enable **Vault File Drop** in Settings → Community plugins.

For an existing installation, disable the plugin, replace `main.js`, `manifest.json`, and `styles.css`, then enable it again. Preserve `data.json` to retain your preferences.

## File behavior

Existing destination names receive numbered suffixes. Copying into the current folder creates a duplicate; moving there does nothing. External move permanently removes the source only after successful verification and tab switching. Only the dragged file is processed; linked assets are not imported with it.

## Privacy and compatibility

Local-only operation. No network requests, accounts, telemetry, or advertisements. Windows Obsidian 1.14.4 integration and automated tests cover internal/external file operations, link updates, scrolling, and shortcut recording. Other platforms and third-party themes have not received full interactive acceptance testing.

This is an independent Obsidian community plugin. Community Directory submission and approval are separate from this GitHub release; no existing marketplace listing is claimed.

**License:** No License.
