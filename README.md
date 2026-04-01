# OnyxGlass — CopyQ Theme

A polished, deep-blue dark theme for [CopyQ](https://hluk.github.io/CopyQ/) clipboard manager.
OnyxGlass features a near-black navy palette with soft periwinkle-blue accent highlights,
smooth gradient hover/selection states, slim 5 px scrollbars, and refined rounded-corner
menus — delivering a clean, professional look that fits right in on any modern desktop.

## Color Palette

| Role | Hex |
|---|---|
| Background | `#101318` |
| Alt background | `#141922` |
| Foreground | `#d6dce7` |
| Selection background | `#8fb4ff` |
| Selection foreground | `#f4f8ff` |
| Edit / find background | `#0d1117` |
| Accent / highlight | `#8fb4ff` |

## Installation

### Option A — Copy theme file (recommended)

1. Download `OnyxGlass.ini` from this repository.
2. Copy it into the CopyQ **themes** folder:
   - **Windows:** `%APPDATA%\copyq\themes\`
   - **Linux:** `~/.config/copyq/themes/`
   - **macOS:** `~/Library/Application Support/copyq/themes/`
3. Open CopyQ → **File ▸ Preferences ▸ Appearance** and select **OnyxGlass** from the theme list.

### Option B — Load via Preferences dialog

1. Open CopyQ → **File ▸ Preferences ▸ Appearance**.
2. Click **Load theme…** and browse to `OnyxGlass.ini`.

## Submitting to CopyQ upstream

If you would like this theme included as a built-in CopyQ theme, follow these steps to open
a pull request against the official CopyQ repository:

1. **Fork** [hluk/CopyQ](https://github.com/hluk/CopyQ) on GitHub.
2. **Clone** your fork locally:
   ```
   git clone https://github.com/<your-username>/CopyQ.git
   cd CopyQ
   ```
3. **Copy** `OnyxGlass.ini` into `shared/themes/`:
   ```
   cp /path/to/OnyxGlass.ini shared/themes/onyxglass.ini
   ```
4. **Commit and push** the change to a new branch:
   ```
   git checkout -b theme/onyxglass
   git add shared/themes/onyxglass.ini
   git commit -m "Add OnyxGlass dark theme"
   git push origin theme/onyxglass
   ```
5. Open a **Pull Request** on [hluk/CopyQ](https://github.com/hluk/CopyQ) from your branch,
   describing the theme and linking back to this repository.

## License

This theme is released as free and open-source software under the
[MIT License](LICENSE).
