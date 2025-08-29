# Utility Materials Protocol Theme

A VSCode theme inspired by industrial safety design and utility energy solutions, featuring safety orange colors and optional TV static effects.

![Theme Preview](https://img.shields.io/badge/theme-utility--materials-ff9500)

## Features

- **Safety Orange Color Palette**: Industrial-grade safety orange replacing traditional red hues
- **Industrial Dashboard Design**: Dark backgrounds with high-contrast utility colors
- **TV Static Animation**: Optional background static effect for that authentic industrial monitor feel
- **Utility Materials Branding**: Subtle industrial design elements

## Installation

Search for `Utility Materials Theme` in your VSCode fork of chose.

## TV Static Effect (Optional)

To enable the authentic industrial monitor TV static effect:

### Prerequisites
Install the **Custom UI Style** extension:
1. Open VSCode Extensions (`Cmd+Shift+X` / `Ctrl+Shift+X`)
2. Search for "Custom UI Style" by subframe7536
3. Install the extension

### Setup Static Effect
1. Copy the contents of `tv-static.css`
2. Press `Cmd+Shift+P` / `Ctrl+Shift+P`
3. Type "Custom UI Style: Edit CSS"
4. Paste the CSS content
5. Save and reload VSCode

**Note**: VSCode will show an "unsupported" warning - this is normal when using custom CSS.

### Alternative Static Setup (Settings.json)
Add this to your VSCode `settings.json`:

```json
{
  "custom-ui-style.css": "path/to/tv-static.css",
  "custom-ui-style.imports": ["tv-static.css"]
}
```

## Color Palette

| Element | Color | Usage |
|---------|-------|-------|
| Primary Orange | `#ff9500` | Keywords, active elements, borders |
| Safety Orange | `#ff6600` | Errors, warnings, critical elements |
| Industrial Dark | `#1a0a00` | Backgrounds, panels |
| Utility Green | `#00ffc8` | Success states, cursors |
| Warning Yellow | `#ffcc00` | Cautions, modifications |

## Markdown Preview Enhanced

### Prerequisites
Install the **Markdown Preview Enhanced** extension:
1. Open VSCode Extensions (`Cmd+Shift+X` / `Ctrl+Shift+X`)
2. Search for "Markdown Preview Enhanced" by shd101wyy
3. Install the extension

### Setup Static Effect
1. Copy the contents of `markdown-preview-enhanced.less`
2. Press `Cmd+Shift+P` / `Ctrl+Shift+P`
3. Type "Markdown Preview Enhanced: Customize CSS"
4. Paste the LESS content

### Editor View
The main editor features safety orange syntax highlighting with industrial dark backgrounds.

### TV Static Effect
When enabled, the subtle static animation provides an authentic industrial monitor experience without interfering with code readability.

## Compatibility

- VSCode 1.74.0+
- All major programming languages
- Light and dark variants (dark theme)

## Troubleshooting

### Theme Not Appearing
- Ensure the extension is properly installed
- Try reloading VSCode (`Cmd+R` / `Ctrl+R`)
- Check that the theme name matches exactly

### Static Effect Issues
- Verify Custom UI Style extension is installed and enabled
- Check that CSS file path is correct
- Restart VSCode after making changes
- Reduce static opacity if effect is too strong

## License

MIT License - Feel free to modify and distribute.

## Acknowledgments

- Inspired by the Cyberpunk SCARLET Protocol theme
- Color palette based on industrial safety standards
- Built for the utility materials community

---

**UTIL-MAT Protocol Activated** 🔧⚡