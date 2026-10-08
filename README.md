# Personal Cable TV Jellyfin Companion

A third-party Jellyfin plugin repository for **Personal Cable TV Jellyfin Companion**.

> **Personal Cable TV is required.** This repository contains only the optional Jellyfin Companion plugin.  
> Download and install the main Personal Cable TV server first from:  
> https://github.com/akaidragon123k/Personal-Cable-TV

> **Media is not included.** Neither this plugin nor Personal Cable TV provides movies, TV shows, cartoons, anime, or subscription content. You must use your own legally obtained media library.

This Companion integrates Personal Cable TV with supported Jellyfin clients and adds a cable-style viewing experience on top of the Personal Cable TV/Jellyfin Live TV setup.

## Requirements

Before installing this plugin, you need:

- A working **Personal Cable TV** server
- A working **Jellyfin** server connected to Personal Cable TV
- Personal Cable TV M3U/XMLTV Live TV already configured in Jellyfin
- Jellyfin Server/Web **10.11.10** for the current Companion release
- Your own media library
- A supported Jellyfin client

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

For Roku TVs/devices, use the dedicated **P.Cable TV Companion Roku app** for the full Personal Cable TV experience once that Roku app is publicly available.

## Recommended installation from Jellyfin

Add this repository once in Jellyfin:

**Repository name**  
`Personal Cable TV Companion`

**Repository URL**  
`https://raw.githubusercontent.com/akaidragon123k/PersonalCableTV-Jellyfin-Companion/main/manifest.json`

Then:

1. Open Jellyfin Dashboard.
2. Go to **Plugins**.
3. Open **Repositories / Manage Repositories**.
4. Add the repository name and URL above.
5. Save.
6. Open the plugin catalog.
7. Find **Personal Cable TV Jellyfin Companion**.
8. Install the latest compatible version.
9. Restart Jellyfin when requested.

Future Companion releases can then appear in Jellyfin's revision history and be installed from the plugin page without manually downloading each ZIP.

## What the Companion changes

The Companion changes the **Jellyfin-side presentation and controls** for Personal Cable TV. It is not a replacement for the Personal Cable TV server.

It provides or preserves:

- Personal Cable TV guide presentation
- On Now / current-live experience
- Remote-friendly TV navigation
- Live channel surfing on verified LG/webOS clients
- Cable-style restrictions for Personal Cable TV live playback

## What the Companion does not do

- It does not provide media.
- It does not download movies or TV shows.
- It does not replace the Personal Cable TV server.
- It does not replace Jellyfin.
- It does not modify your NAS media.
- It does not delete, rename, move, or overwrite your media.
- It does not guarantee identical behavior on every Jellyfin client.

## Need Personal Cable TV first?

Main project and server download:

https://github.com/akaidragon123k/Personal-Cable-TV

## Manual release download

If repository installation is not available, the current release is also published here:

https://github.com/akaidragon123k/PersonalCableTV-Jellyfin-Companion/releases/tag/v0.1.0.1

## Compatibility

- **Verified:** Jellyfin 10.11.10 + LG/webOS
- **Limited:** Jellyfin Roku client
- **Other clients:** not yet verified

## Safety

The Companion does not modify Personal Cable TV production media, Jellyfin libraries, users, watch history, recordings, M3U/XMLTV configuration, or NAS media.

Back up plugin configuration before replacing a manual installation, and keep your Personal Cable TV media mount read-only.

## License

GPL-2.0-only.
