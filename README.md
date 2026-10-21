# Shebang Light for Omarchy

A warm, light Omarchy theme based on Shebang's visual identity: ivory surfaces,
dark burgundy text, yellow selections and turquoise window borders.
Terminal text colors use darker companion shades for readability.

![Shebang Light wallpaper](backgrounds/shebang-light.png)

## Install

```sh
omarchy theme install https://github.com/sdnit-se/omarchy-shebang-light-theme
```

Installation also activates the theme. To select it again later:

```sh
omarchy theme set shebang-light
```

Tested with Omarchy 4.0.6-1. Omarchy generates application configurations from
`colors.toml`. Existing fonts are preserved. The icon preference is Yaru.

## Files

- `colors.toml`: palette and window borders.
- `icons.theme`: icon theme preference.
- `backgrounds/shebang-light.png`: 3840 × 2400 wallpaper.
- `source/shebang-light.svg`: editable vector wallpaper with official logo paths.

The wallpaper is rendered directly from SVG. The standard and bright terminal
accent colors, foreground, muted text and main accent have at least 4.5:1
contrast against the ivory background.

## Optional daytime scheduling

Installing this theme does not install or change a scheduler. If you already
use a daytime/nighttime theme script, set its daytime theme to `Shebang Light`
(or slug `shebang-light`) and keep your preferred nighttime theme.
An existing scheduler may otherwise override a manual theme selection.

## Brand assets and permissions

The Shebang name and logo remain the property of their respective rights holders.
This repository supplies the branded wallpaper for use with this theme; it does
not grant rights to use the logo as your own identity or imply endorsement.
No general open-source license is granted by this repository. Contact the
repository owner for permission for other reuse or redistribution.
