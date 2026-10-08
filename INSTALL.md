# Installation

## Before you install

Personal Cable TV Jellyfin Companion is an **optional plugin**. It does not work as a standalone media service.

You need:

- Personal Cable TV installed and working
- Jellyfin installed and connected to Personal Cable TV
- Personal Cable TV M3U and XMLTV configured in Jellyfin Live TV
- Jellyfin Server/Web 10.11.10 for Companion version 0.1.0.1
- Your own legally obtained media library

Main Personal Cable TV project:

https://github.com/akaidragon123k/Personal-Cable-TV

## Recommended: Jellyfin repository

1. Open Jellyfin Dashboard.
2. Go to **Plugins**.
3. Open **Repositories / Manage Repositories**.
4. Add a repository named **Personal Cable TV Companion**.
5. Use this URL:

   `https://raw.githubusercontent.com/akaidragon123k/PersonalCableTV-Jellyfin-Companion/main/manifest.json`

6. Save the repository.
7. Open the plugin catalog.
8. Find **Personal Cable TV Jellyfin Companion**.
9. Install the latest compatible version.
10. Restart Jellyfin when requested.
11. Return to the plugin page and confirm the plugin shows **Active**, the expected version, developer **Akai Dragon**, and repository **Personal Cable TV Companion**.

## Existing manual installs

If you already installed an older Companion manually:

1. Back up the existing plugin directory and configuration.
2. Add this repository first.
3. Confirm Jellyfin shows the repository version in Revision History.
4. Install the repository version from the existing plugin page.
5. Restart Jellyfin if requested.
6. Confirm the new version is Active before removing any backup.

Do not delete media, Jellyfin libraries, Personal Cable TV data, or server configuration during this migration.

## Updates

When a newer compatible Companion version is published in this repository, Jellyfin can display it in the plugin's Revision History. Install the new revision from Jellyfin and restart when requested.

## Roku note

The Jellyfin Roku client has limited Companion behavior. For Roku TVs/devices, use the dedicated **P.Cable TV Companion Roku app** for the full live-TV experience once that app is publicly available.

## Media notice

This plugin and Personal Cable TV do not include movies, TV shows, cartoons, anime, or subscription content. Users must provide their own legally obtained media.
