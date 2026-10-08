# Personal Cable TV Jellyfin Companion

A third-party Jellyfin plugin repository for **Personal Cable TV Jellyfin Companion**.

This Companion integrates Personal Cable TV with supported Jellyfin clients and preserves the cable-style live-TV experience.

## Current release

**Version:** 0.1.0.1  
**Target:** Jellyfin Server/Web 10.11.10  
**Plugin GUID:** `f13517a4-d3c0-46b8-b1b0-15993d09139f`

### Verified LG / webOS behavior

- Up changes to the previous/lower Personal Cable TV channel during playback.
- Down changes to the next/higher channel.
- Channel surfing works without returning to the Guide.
- Pause, rewind, fast-forward, seek/scrub, and chapter-skip remain blocked for Personal Cable TV live playback.

### Roku Jellyfin-client limitation

The Jellyfin Roku client does not currently support all Companion playback behavior correctly:

- Up/Down channel surfing does not work during playback.
- Pause may remain available.

For Roku TVs/devices, use the dedicated **P.Cable TV Companion Roku app** for the full Personal Cable TV experience.

## Install from Jellyfin

Add this repository once in Jellyfin:

**Repository name**  
`Personal Cable TV Companion`

**Repository URL**  
`https://raw.githubusercontent.com/akaidragon123k/PersonalCableTV-Jellyfin-Companion/main/manifest.json`

Then open Jellyfin's plugin catalog and install **Personal Cable TV Jellyfin Companion**.

After future releases are added to this repository manifest, Jellyfin can discover the newer plugin version without requiring users to manually find the ZIP on GitHub.

## Manual release download

`https://github.com/akaidragon123k/PersonalCableTV-Jellyfin-Companion/releases/tag/v0.1.0.1`

## Safety

The Companion does not modify Personal Cable TV production media, Jellyfin libraries, users, watch history, recordings, M3U/XMLTV configuration, or NAS media.

## Compatibility

- **Verified:** Jellyfin 10.11.10 + LG/webOS
- **Limited:** Jellyfin Roku client
- **Other clients:** not yet verified

## License

GPL-2.0-only.
