# Gruvbox for renCal

The retro groove [Gruvbox](https://github.com/morhetz/gruvbox) color scheme for
[renCal](https://rencal.org), with canonical medium-contrast dark and light
variants.

[Install in renCal](rencal://plugin/install?repo=t4t5%2Frencal-theme-gruvbox)

## Themes

- **Gruvbox Dark** — medium dark background with bright Gruvbox accents
- **Gruvbox Light** — medium light background with neutral Gruvbox accents

## Installation

Use the **Install in renCal** link above, or install from a terminal on Linux:

```sh
rencal plugin install t4t5/rencal-theme-gruvbox
```

The themes appear under **Settings → Themes** after installation. Gruvbox for
renCal requires renCal 0.8.0 or newer, the first version with theme-plugin
support.

## Attribution

This is an independent port and is not an official Gruvbox project. The palette
comes from Pavel Pertsev's original
[morhetz/gruvbox](https://github.com/morhetz/gruvbox) project, which is licensed
under the MIT/X11 license.

The palette is pinned to upstream commit
[`ef8864bb42bf244f0295d1c5a403b27e3d139695`](https://github.com/morhetz/gruvbox/commit/ef8864bb42bf244f0295d1c5a403b27e3d139695).
See [LICENSE](LICENSE) for the license terms and attribution.

## Releases and updates

Both variants are released and updated together. Publishing an update requires
bumping `version` in `rencal-plugin.toml`; a stable GitHub release tag must match
that version, with an optional `v` prefix (for example, `v1.0.0`).
