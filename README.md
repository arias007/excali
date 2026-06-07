# excali

A modified Excalidraw plugin for Obsidian.

This repository contains a custom build of the Obsidian Excalidraw plugin, tuned for handwriting notes, image annotation, interactive Markdown import, and a more compact drawing workflow.

## Download

The ready-to-install build is available from the latest GitHub Release:

https://github.com/arias007/excali/releases/latest

Download the ZIP file, unzip it, and place the plugin files into your Obsidian plugin folder.

## What changed

- Compact top toolbar with common actions grouped in one place.
- Side and bottom controls moved into the main toolbar area.
- Undo and redo moved toward the left side for faster access.
- Selection actions such as copy, delete, and edit are shown closer to the selected element.
- Pen mode supports secondary pen presets.
- Secondary pens are shown as a horizontal row when the pen tool is active.
- The `+` button adds more pen presets.
- Each pen remembers its own color, stroke width, style, and drawing settings.
- Pen preset icons update to reflect the current configuration.
- Long-press a secondary pen to delete that preset.
- Secondary pens are hidden when switching away from the pen tool.
- Interactive Markdown and image import layering was adjusted so handwriting stays above imported images.
- Imported Markdown images now keep better position and sizing.
- Imported content frames are adjusted to better fit annotation workflows.

## Installation

The plugin ID is intentionally still:

```text
obsidian-excalidraw-plugin
```

This keeps it compatible with the existing Obsidian Excalidraw plugin folder, for example:

```text
E:/note/.obsidian/plugins/obsidian-excalidraw-plugin
```

For manual installation, copy the built plugin files into:

```text
<your vault>/.obsidian/plugins/obsidian-excalidraw-plugin
```

Then enable the plugin in Obsidian settings.

## Build

Install dependencies:

```powershell
npm install
```

Build the plugin:

```powershell
npm run build
```

Typical build output includes:

```text
main.js
manifest.json
styles.css
```

## Notes

- This is a custom modified build, not the official upstream release.
- The plugin ID has not been renamed to avoid breaking the current Obsidian installation path.
- Back up the original Excalidraw plugin folder before replacing it.

## Upstream

Based on the original project:

https://github.com/zsviczian/obsidian-excalidraw-plugin

The original license is preserved in `LICENSE`.
