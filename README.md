# Bookshelf themes for T3 Code

Two low-glare, book-style **light** themes for [T3 Code](https://t3.codes).

| Theme | Look |
|---|---|
| **Bookshelf Paper** | Soft cream page, blue-grey ink accent |
| **Bookshelf Calm** | Warm sepia page, rust accent |

Body text contrast is about 10 to 12:1. Every muted, status and button colour is at least 4.5:1 (WCAG AA).

## Install

### In the app

Settings → Appearance → **Add a theme** → drop both files from `themes/` onto the dialog → select one.

### From the CLI

```bash
git clone https://github.com/vatana7/t3code-bookshelf-themes.git
cd t3code-bookshelf-themes
t3 theme set themes/Bookshelf-Paper.json --id bookshelf-paper --base-dir "${T3CODE_HOME:-$HOME/.t3}"
t3 theme set themes/Bookshelf-Calm.json  --id bookshelf-calm  --base-dir "${T3CODE_HOME:-$HOME/.t3}"
```

If `t3` is not on your PATH, use `npx --yes t3@latest theme set ...`. The last theme you install becomes the active one.

Both themes are light halves. You can pair them with any dark half in Settings → Appearance.

## Contrast (WCAG ratios)

| Check | Paper | Calm |
|---|---|---|
| Body text on page | 11.8:1 | 10.3:1 |
| Muted text on page | 5.3:1 | 5.7:1 |
| Muted text on sidebar | 4.8:1 | 5.1:1 |
| Text on user message bubble | 10.2:1 | 8.9:1 |
| Button text on accent | 6.1:1 | 5.4:1 |
| Error / warning text on page | 5.7 / 4.8:1 | 4.9 / 5.0:1 |
| Code text on code block | 10.8:1 | 9.4:1 |

## License

MIT
