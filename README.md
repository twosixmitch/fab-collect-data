# FaB Collect data

Card database and product images for [FaB Collect](https://github.com/twosixmitch/fab-collect), a free collection tracker for the Flesh and Blood trading card game. The app downloads new sets from here, so a new set doesn't need an App Store or Play Store update.

## What's here

| Path | Contents |
| --- | --- |
| `database.json` | The latest card database: its version, download URL, size, sha256 and the minimum app version that can read it |
| [Releases](../../releases) | Each database as `fab_collect_db_<version>.zip`, tagged `db-<version>` |
| `products/` | Product images as WebP, named `<slug>_<hash>.webp` |

Published versions are never overwritten. A changed database gets a new version number, and a changed image gets a new file name.

## Use

This data exists to serve the FaB Collect app. It's free and will stay free: there's no charge, account or key to use it.

Card and product images are used in their original form, only converted to WebP and resized.

## Disclaimer

FaB Collect is in no way affiliated with Legend Story Studios. Legend Story Studios®, Flesh and Blood™, and set names are trademarks of Legend Story Studios. Flesh and Blood characters, cards, logos, and art are property of Legend Story Studios.

© Legend Story Studios

## Removal requests

If you're from Legend Story Studios, or hold rights to anything here, and want something removed, open an issue in this repo. It will be taken down promptly.
