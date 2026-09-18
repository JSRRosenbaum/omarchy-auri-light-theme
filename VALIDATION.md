# Auri Light validation

PASS: all 19 official templates rendered in disposable HOME; light mode resolver verified.
PASS: generated TOML/JSON/INI parsed; no unresolved placeholders.
PASS: all 20 text/accent roles >=4.5:1 on all five tested surfaces (including selection).
PASS: active border >=3:1 on main background.

| Role | Color | On porcelain | Worst tested surface |
|---|---|---:|---:|
| foreground | `#343a3d` | 10.71:1 | 8.51:1 |
| dark_foreground | `#565650` | 6.85:1 | 5.44:1 |
| light_foreground | `#41494c` | 8.54:1 | 6.78:1 |
| bright_foreground | `#252d31` | 13.00:1 | 10.32:1 |
| muted | `#655e55` | 5.93:1 | 4.71:1 |
| accent | `#285f68` | 6.66:1 | 5.29:1 |
| red | `#934c50` | 5.75:1 | 4.56:1 |
| yellow | `#795719` | 6.11:1 | 4.85:1 |
| orange | `#865035` | 6.06:1 | 4.82:1 |
| green | `#49613f` | 6.36:1 | 5.05:1 |
| cyan | `#28616a` | 6.48:1 | 5.14:1 |
| blue | `#3c5e7b` | 6.33:1 | 5.02:1 |
| magenta | `#6f547b` | 6.03:1 | 4.79:1 |
| brown | `#76533f` | 6.33:1 | 5.02:1 |
| bright_red | `#884047` | 6.79:1 | 5.39:1 |
| bright_yellow | `#705016` | 6.84:1 | 5.43:1 |
| bright_green | `#405a37` | 7.12:1 | 5.65:1 |
| bright_cyan | `#205b63` | 7.12:1 | 5.65:1 |
| bright_blue | `#325672` | 7.19:1 | 5.71:1 |
| bright_magenta | `#654970` | 7.11:1 | 5.65:1 |

Limits: no desktop activation, live app test, Lua compiler or CSS parser; upstream templates and user overrides remain runtime dependencies. ANSI black matches background by stock contract. Contrast calculations assume opaque colors, not wallpaper/translucency. Palette does not guarantee every arbitrary ANSI foreground/background pairing.

Sources: https://github.com/basecamp/omarchy/blob/9c5482c58dbe4974de337450754885083c91eada/docs/theming.md and matching default/themed templates.
