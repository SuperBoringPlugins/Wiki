# Config.yml

## config
*The configuration options*

### format

**Description:** The format when using the placeholder.  
**Default:** `%mc% %discord%`  
**Aditional Info:** PlaceholderAPI placeholders are allowed.

## ranks
*Defined ranks go here*

__Example__
``` yaml title="config.yml"
ranks:
  mc: #(1)
    - rank1: "Rank 1" #(2)
    - rank2: "Rank 2"
    - rank3: "Rank 3"
  discord: #(3)
    - 000000000000000001: "Level 1" #(4)
    - 000000000000000002: "Level 2"
    - 000000000000000003: "Level 3"
```

1.  Minecraft ranks are defined here
2.  rank1 is the ID, "Rank 1" is the text 
3.  Discord ranks are defined here
4.  000000000000000001 is the id (must be valid discord role id), "Level 1" is the text

There are two lists, minecraft and discord, that each have a list of ranks.

Sort the ranks from the lowest level to the highest level for it to work properly. 

### mc

To give someone a rank, give them the permission `ranky.ID`, where ID is the id in the config.

You can give these permissions in permission plugin groups, one group for each rank.

The player can have multiple groups and it won't break.

### discord

To give someone a rank, give them the role with the ID in the config.

You don't need to remove lower roles, as Ranky will choose the highest rank role they have.
