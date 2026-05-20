# ionicons-ttf

Ionicons packaged as a TTF font for use in Flutter and other native environments.

SVGs are sourced from [ionic-team/ionicons](https://github.com/ionic-team/ionicons) and built into a TTF using [fantasticon](https://github.com/tancredi/fantasticon).

## Releases

Each release includes:
- `ionicons-{version}.ttf` — the font file
- `ionicons-{version}.json` — a map of icon names to codepoints, for use in codegen

## Updating

The **Sync SVGs from Upstream** workflow runs daily at midnight UTC. If upstream has changed, it commits the updated SVGs to main which triggers a new TTF build and release automatically.

The sync can also be triggered manually from the Actions tab.
