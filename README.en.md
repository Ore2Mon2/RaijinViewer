# RaijinViewer

[日本語](README.md) | English

A lightweight image viewer for quickly checking the images in a folder.
Supports JPG / PNG / WebP / GIF.

- Settings, logs and everything else are stored **in the same folder as `RaijinViewer.exe` on Windows** (nothing is written to `%AppData%`), and in `~/Library/Application Support/RaijinViewer` on macOS
- The UI is available in Japanese and English: it follows the OS language (Japanese if the OS language is Japanese, English otherwise), and you can switch at any time by pressing **L**

## Requirements

- Windows 11 (64-bit)
- macOS (Apple Silicon Mac; tested on macOS 26)

## Usage

Drop an image file or a folder onto the window.

### Keyboard

| Key | Action |
|---|---|
| → / ↓, ← / ↑ | Next / previous file |
| Delete | Delete the file (to the Recycle Bin) |
| Shift + Delete, Ctrl + Z | Undo delete |
| Enter | Hide / show the top and bottom bars |
| Backspace | Show / hide the thumbnail panel |
| Home / End | Zoom in / out (1x – 4x) |
| F5, Ctrl + R | Reload the folder |
| H | Show the mouse / keyboard reference |
| V | Show the version information |
| O | Show the recent folders list (↑↓ to select, Enter to open, Esc to close) |
| L | Switch the UI language (Japanese / English) |
| Space | Launch a new window (a separate process) |

### Mouse

| Action | Result |
|---|---|
| Wheel | Previous / next file |
| Forward / back button | Zoom in / out |
| Hold the right button (at 1x) | Magnifier |
| Right-drag (when zoomed) | Pan the image |
| Left double-click | Minimize the window |
| Right double-click | Hide / show the top and bottom bars |
| Left + right buttons together | Show / hide the thumbnail panel |
| Left button + back button together | Delete the file |
| Right-click the bottom-left icon | Show the recent folders list (click to open) |
| Drag a thumbnail / the image | **Copy** the file to a folder in Explorer (Finder) |
| Shift + drag | **Move** the file to a folder in Explorer (Finder) |

## License

Copyright belongs to the developer (Ore2Mon2). See `LICENSE.md` for details.
The licenses of the open-source software used are listed in `THIRD-PARTY-LICENSES.md`.
