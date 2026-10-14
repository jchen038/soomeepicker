# Sumikko Chooser - Android APK Project (v2 with Custom Presets & Art)

This package contains the complete native Android WebView project for **Sumikko Chooser**, including:
- **Authentic San-X Style Sumikko Art** (`app/src/main/assets/index.html`)
- **Configurable Presets File** (`app/src/main/assets/presets-config.js`)
- **Custom Adaptive Shirokuma & Tapioca Launcher Icon** (`app/src/main/res/`)
- **1-Click GitHub Actions APK Builder** (`.github/workflows/build-apk.yml`)

## Customizing Presets (`presets-config.js`)
You can edit `app/src/main/assets/presets-config.js` directly in GitHub or use the in-app **⚙️ Presets** button to customize:
- `maxVisiblePresets`: How many preset chips appear in the top bar
- `title`: Preset button label
- `icon`: Any of the 14 custom SVG icons (`boba`, `hotpot`, `yarn`, `sprout`, `claw`, `cat`, `sweet`, `book`, `game`, `plane`, `music`, `coffee`, `star`, `cart`)
- `color`: Hex pastel background color for the tile
- `options`: Array of choices loaded when tapped
