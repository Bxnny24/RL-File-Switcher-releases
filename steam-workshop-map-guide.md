# Steam Workshop Maps Guide

Steam Workshop maps in RL File Switcher work differently from BakkesPlugins maps.

## Why there is no direct in-app download

Rocket League Workshop files are served by Steam. For many Rocket League Workshop items, Steam rejects anonymous SteamCMD downloads with errors like `Missing decryption key` or `Download item failed`. Downloader websites and tools usually use SteamCMD, cached third-party mirrors, or require Steam account access. RL File Switcher does not store Steam credentials and does not depend on hidden third-party APIs.

## If you own Rocket League on Steam

1. Open the Steam Workshop map from RL File Switcher.
2. Subscribe to the map in Steam.
3. Wait until the Steam client has finished downloading the Workshop item.
4. Return to RL File Switcher.
5. Import the downloaded map file or use the local Steam Workshop file if available.
6. Assign the imported map from Downloaded Maps to an in-game map.

Steam Workshop files are usually stored under a Steam library path like:

`steamapps/workshop/content/252950/<workshop-id>`

## If you only own Rocket League on Epic

You can usually open Steam Workshop pages in the browser, and Steam may still show a Subscribe button. However, Steam often does not download the actual Rocket League Workshop files unless the Steam account has access to the game content. In that case RL File Switcher cannot import anything automatically because no local `.upk` file exists.

For Epic-only users, use one of these options:

- Prefer BakkesPlugins maps when available.
- Manually import a `.zip`, `.upk`, or `.udk` map file from a source you trust.
- Try an external Workshop downloader such as https://steamworkshopdownloader.io/ by pasting the Steam Workshop link there, then import the downloaded file manually in RL File Switcher.

External downloader sites are not controlled by RL File Switcher. They may stop working, use cached mirrors, or fail for some maps.

## If the map is not found

- Make sure Steam has actually downloaded the Workshop item.
- Restart Steam if the Workshop download is stuck at `0 B`.
- Check whether a folder exists under `steamapps/workshop/content/252950/<workshop-id>`.
- If Steam does not download the files, use BakkesPlugins or a trusted manual download source instead.