[items.zip](https://github.com/return-of-modding/ModdingWiki/files/14551142/items.zip)

A neatly organized collection of all vanilla items in gm.constants.  
(Scroll down for usage notes)

![items](https://github.com/return-of-modding/ModdingWiki/assets/78520710/18eeee8a-3e1f-4410-bb7e-8ec62295a2d3)

---

### Setup and Notes

* Copy the file into your mod folder and require it with `Items = require("./items")`.
* `Items.rarities` is an enum containing `.white`, `.green`, `.red`, `.orange`, `.yellow`, and `.purple`.
* `Items.items` is the main table containing all item data entries.
  * Each item entry is in the format `{name, gm.constant, Item.rarity}`.
  * There are also individual rarity tables (e.g., `Items.white_items`).


### Functions

`Items.get_item_names(rarity)`  
Returns a table containing all item names of a rarity, or all items if none is specified.

`Items.get_item_constants(rarity)`  
Returns a table containing all item gm.constants of a rarity, or all items if none is specified.

`Items.find_item(name_or_const)`  
Returns the table index of the item and its data (two return values), or -1 and nil if the item doesn't exist.
