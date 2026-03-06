# Figma UI Kit (Import-ready)

This folder contains a ready-to-import UI kit for Figma based on this project style.

## What is inside

- `figma-ui-kit.svg` - main component board (drag and drop into Figma)
- `design-tokens.json` - color/typography/spacing tokens (Tokens Studio compatible schema)
- `component-map.md` - how to convert imported layers into reusable Figma components

## Quick import (2-3 minutes)

1. Open Figma and create a new file.
2. Drag `figma-ui-kit.svg` directly onto the canvas.
3. Select all imported frames and run `Frame selection` if needed.
4. Install `Tokens Studio for Figma` plugin.
5. In plugin, import `design-tokens.json`.
6. Apply variables/styles to color and text layers.
7. Publish as a Team Library.

## Recommended setup after import

- Font family for UI text: `Syne`
- Font family for technical values: `JetBrains Mono`
- Convert blocks in `COMPONENTS` section into component sets with variants:
  - `Button / Type=Primary|Ghost|Danger`
  - `Badge / Status=Ok|Warn|Error|Info|Dbt`
  - `Input / State=Default|Focus|Error`
  - `Card / Type=Default|Wide`

## Export options from Figma

- PNG/SVG/PDF for presentations and docs
- CSS from Inspect panel
- Variables/tokens via plugin export
