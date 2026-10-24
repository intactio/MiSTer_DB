# intactio's MiSTer database

A custom database for the [MiSTer Downloader](https://github.com/MiSTer-devel/Downloader_MiSTer), so `update` / `update_all` installs and updates my arcade cores.

| Core | Games | Source |
|---|---|---|
| Nekketsu | Super Dodge Ball (US), Nekketsu Koukou Dodgeball Bu (Japan) | [Arcade-Nekketsu_MiSTer](https://github.com/intactio/Arcade-Nekketsu_MiSTer) |
| DragonBowl | Dragon Bowl (set 1, encrypted program), Dragon Bowl (set 2, unencrypted program) | [Arcade-DragonBowl_MiSTer](https://github.com/intactio/Arcade-DragonBowl_MiSTer) |

Installed files:

- `_Arcade/cores/Nekketsu_YYYYMMDD.rbf`
- `_Arcade/Super Dodge Ball (US).mra`
- `_Arcade/_alternatives/_Super Dodge Ball/Nekketsu Koukou Dodgeball Bu (Japan).mra`
- `_Arcade/cores/DragonBowl_YYYYMMDD.rbf`
- `_Arcade/Dragon Bowl (set 1, encrypted program).mra`
- `_Arcade/_alternatives/_Dragon Bowl/Dragon Bowl (set 2, unencrypted program).mra`

The cores (`.rbf`) are downloaded from the cores' GitHub releases; the MRAs are kept in this repository, copied from the core repositories. **ROMs are not included**: put your own MAME sets (`spdodgeb.zip`, `nkdodge.zip`, `drgnbowl.zip`, `drgnbowla.zip`) in `games/mame/`.

## Install

1. Download [downloader_intactio_MiSTer_DB.zip](https://raw.githubusercontent.com/intactio/MiSTer_DB/db/downloader_intactio_MiSTer_DB.zip).
2. Extract `downloader_intactio_MiSTer_DB.ini` to the root of the SD card, next to `downloader.ini`.
3. Run `update` or `update_all`.

Or add these lines to the end of `downloader.ini`:

```ini
[intactio/MiSTer_DB]
db_url = https://raw.githubusercontent.com/intactio/MiSTer_DB/db/db.json.zip
```

## Support

The cores are free, with nothing locked behind tips. If you enjoy them, you can support the work on [Ko-fi](https://ko-fi.com/intactio).

Built with [DB-Template_MiSTer](https://github.com/theypsilon/DB-Template_MiSTer) by theypsilon.
