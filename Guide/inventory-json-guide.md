# Create inventory.json

RL File Switcher can import your owned Rocket League items from a BakkesMod `inventory.json` file.

## What You Need

- Rocket League on PC
- BakkesMod
- Better Inventory Export plugin

Install the plugin from [bakkesplugins.com/plugin/155](https://bakkesplugins.com/plugin/155), or install it through the BakkesMod Plugin Manager with plugin ID `155`.

## Export From Rocket League

1. Start BakkesMod.
2. Start Rocket League with the account you want to export.
3. Open the BakkesMod menu with `F2`.
4. Go to `Plugins`.
5. Open `Better Inventory Export`.
6. Click `Dump to json`.

The file will be saved here:

```text
%AppData%\bakkesmod\bakkesmod\data\inventory.json
```

You can also run this command in the BakkesMod console:

```text
invent_dump_better json
```

## Import Into RL File Switcher

1. Open RL File Switcher.
2. Open `Accounts`.
3. Find the same Steam or Epic account you exported from.
4. Click the import button next to that account.

Existing manually marked owned items are kept. The import only adds matched items.

## Multiple Accounts

`inventory.json` does not include the Steam or Epic account ID, and the plugin overwrites the same file every time.

For each account:

1. Log into that account in Rocket League.
2. Export `inventory.json`.
3. Import it next to the same account in RL File Switcher.
