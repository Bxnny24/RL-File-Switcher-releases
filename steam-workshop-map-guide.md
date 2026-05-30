# Steam Workshop Maps Guide

Steam Workshop maps in RL File Switcher work differently from BakkesPlugins maps.

## Why there is no direct download

Rocket League Workshop files are served by Steam. For many Rocket League Workshop items, Steam rejects anonymous SteamCMD downloads with errors like `Missing decryption key` or `Download item failed`. Downloader websites and tools usually use SteamCMD, cached third-party mirrors, or require Steam account access. RL File Switcher does not store Steam credentials and does not depend on third-party mirrors.

## How to import a Steam Workshop map

1. Open the Steam Workshop map from RL File Switcher.
2. Subscribe to the map in Steam.
3. Wait until the Steam client has finished downloading the Workshop item.
4. Return to RL File Switcher.
5. Press the Steam map link/import action again. If the map exists locally, RL File Switcher imports the `.upk` file.
6. Assign the imported map from Downloaded Maps to an in-game map.

## If the map is not found

- Make sure Steam has actually downloaded the Workshop item.
- Restart Steam if the Workshop download is stuck at `0 B`.
- Verify that Rocket League Workshop files exist under a Steam library path like `steamapps/workshop/content/252950/<workshop-id>`.
- If Steam does not download the files, the Steam account may not have access to Rocket League Workshop content.

## Epic-only note

If you only own Rocket League on Epic, Steam may allow you to view or subscribe to Workshop pages but still refuse to download the actual files. In that case, use BakkesPlugins maps or manually import a `.zip`, `.upk`, or `.udk` map file from a source you trust.