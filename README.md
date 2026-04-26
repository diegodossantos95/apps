# Apps

Public site for support, privacy, and terms across apps I publish.

Served via GitHub Pages: **https://diegodossantos95.github.io/apps/**

## Structure

```
apps/
├── index.html          # Landing — links to each app
├── assets/style.css    # Shared styles
└── margin/             # Margin (iOS) — The Reader's Companion
    ├── index.html      # About
    ├── support.html    # Support page (linked from App Store Connect)
    ├── privacy.html    # Privacy Policy (linked from App Store Connect)
    └── terms.html      # Terms of Use / EULA addendum
```

## Issues = Support

This repository's [Issues](https://github.com/diegodossantos95/apps/issues) are the public support channel. Please use the templates when filing.

## Adding another app later

Drop a new sibling folder (e.g. `next-app/`) with the same set of pages, then add a card on `index.html`. Pages URLs stay stable forever as long as folder names don't change.
