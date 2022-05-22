# Storage.yml

NOTE: This file is used by the plugin, no manual editing should be needed.

## Default (if you broke yours)

``` yaml title="storage.yml"
_note: This file is used for storing player data to use in Discord-to-minecraft or Minecraft-to-discord while the linked account is offline
storage: {}
```

## Example

``` yaml title="storage.yml"
#(1)
storage:
  2007ed35-57c0-4d43-8814-57032e70c67f: #(2)
    username: AstroSquared #(3)
    mc: rank1 #(4)
    discord: 000000000000000001 #(5)
```

1.  `_note` is removed because it's not required
2.  The UUID of the player
3.  The username of the player
4.  The minecraft rank of the player, see [config#ranks](/config#ranks)
5.  The discord rank of the player, see [config#ranks](/config#ranks)