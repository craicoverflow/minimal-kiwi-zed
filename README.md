# Minimal Kiwi for Zed

A port of the [Minimal Kiwi](https://github.com/pranjal-barnwal/minimal-kiwi) VS Code theme for [Zed](https://zed.dev).

Dark, minimal, and easy on the eyes — near-black background with a green accent and carefully chosen syntax colors.

## Preview

| Element | Color |
|---|---|
| Background | `#212121` |
| Foreground | `#ecffff` |
| Accent | `#82cd64` |
| Strings | `#90cc89` |
| Keywords | `#89DDFF` |
| Types | `#FFCB6B` |
| Functions | `#6b9aff` |
| Properties | `#F07178` |
| Comments | `#828989` |

## Installation

### Manual

1. Download `minimal-kiwi.json` and place it in your Zed themes directory:

   ```sh
   mkdir -p ~/.config/zed/themes
   curl -o ~/.config/zed/themes/minimal-kiwi.json \
     https://raw.githubusercontent.com/craicoverflow/minimal-kiwi-zed/main/minimal-kiwi.json
   ```

2. Open `~/.config/zed/settings.json` and set the theme:

   ```json
   "theme": {
     "mode": "dark",
     "dark": "Minimal Kiwi"
   }
   ```

   Zed hot-reloads themes — no restart needed.

### Via Zed Theme Selector

Open the command palette (`cmd+shift+p`) → `zed: open theme selector` → search for **Minimal Kiwi**.

> Note: this requires the theme file to already be in `~/.config/zed/themes/`.

## Credits

Original theme by [pranjal-barnwal](https://github.com/pranjal-barnwal/minimal-kiwi). Ported to Zed by [craicoverflow](https://github.com/craicoverflow).

## License

MIT — see [LICENSE](LICENSE).
