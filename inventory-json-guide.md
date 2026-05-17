# Create inventory.json with BakkesMod

RL File Switcher can import owned items from the `inventory.json` file created by the Better Inventory Export BakkesMod plugin.

Important: `inventory.json` does not contain a Steam or Epic account ID. Make sure Rocket League is logged into the account you want to import, then import the file with the matching account row in RL File Switcher.

## Requirements

- Rocket League on PC
- BakkesMod
- Better Inventory Export plugin

Plugin repository: [Bakkes/BetterInventoryExport](https://github.com/Bakkes/BetterInventoryExport)

## Create the file

1. Install and start BakkesMod.
2. Install the Plugin on https://bakkesplugins.com/plugin/155 or through the Plugin manager via the ID "155" in Bakkesmod.
3. Start Rocket League with the account you want to export. With EAC dissabled.
4. Open the BakkesMod menu with `F2`.
5. Open the `Plugins` tab.
6. Select `Better Inventory Export`.
7. Click `Dump to json`.


On a typical Windows install this looks like:

```text
C:\Users\<your-user>\AppData\Roaming\bakkesmod\bakkesmod\data\inventory.json
```

## Import into RL File Switcher

1. Open RL File Switcher.
2. Open `Accounts`.
3. Find the same Steam or Epic account that was active in Rocket League during the export.
4. Click the import button next to that account.

The import adds matched items to that account's owned-item list. Existing manually marked items are kept.

## Exporting multiple accounts

The Better Inventory Export plugin always writes to the same `inventory.json` path. If you want to import multiple accounts:

1. Log into Rocket League with account A.
2. Export `inventory.json`.
3. Import it next to account A in RL File Switcher.
4. Switch Rocket League to account B.
5. Export again.
6. Import it next to account B in RL File Switcher.
