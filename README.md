# CustomEnchantsPE

### Description
This plugin adds a whole bunch of awesome new Items and enchantments that are independent of the Minecraft Enchantment system.

This plugin is a port of the original PC plugin for Bukkit. I will try to make everything work similarly to the PC plugin.

For Suggestions/Commissions/Bugs/etc., create an issue.

### Commands
- /ce - The main command node for Custom Enchantments
Please note that for any command after the main node, you do not have to enter it's full name, the first letter is enough (Example: /ce list = /ce l).

Words in angle Brackets ( < > ) mean that the argument is required, while words written in square Brackets ( [ ] ) are optional.

- /ce runecrafting - Opens the runecrafting inventory.
- /ce menu - Opens an inventory menu for navigating and obtaining Custom Enchantments and Items.
- /ce reload - Reloads the CE config.
- /ce remove [Enchantment] - Removes an enchantment (or all of them) from an item.
- /ce list <Enchantment/Item> - Lists all Custom Enchantments or Items.
- /ce enchant [Required material] <Enchantment> [level] - Adds the specified Enchantment to the item in your hand. If a required material is given, the command will only work if the player holds that item. If an item already has the enchantment, the level will be increased.
- /ce item <Item> - Transforms the item in the player's hand into the specified Custom Item.
- /ce change <Name/Lore> <Color/Set/Add/Reset> [New Value] - Allows you to change the name/lore of the item in your hand
- /ce give <Player> <Material> <Item/Custom or Vanilla Enchantment:Level> [Custom or Vanilla Enchantment:Level] ... - Gives the target player an item with the set material containing the given Enchantments. Please note that the Material has to be either the Minecraft material ID or the Bukkit material ID. The same goes for the Vanilla enchantment names. You can add infinite vanilla and custom enchantments to the item using this command.

### Sign Shops
You can sell Enchantments by setting up a sign in the following format:

- "[CustomEnchant]" (Without the "s) as the first line.
- The Enchantment you want to sell as the second line.
- The cost of the enchantment as the fourth line. This requires Vault and a compatible economy plugin

Players that do not have the enchantment will have the enchantment applied to their current item, if they already have the enchantment they are trying to buy, the level of the enchantment will increase by 1, up to the specified maximum level of the Enchantment (Can be set in the config).

### CE-Menu
You can set a price for the Items/Enchantments through the config. The items and enchantments can then be bought in /ce menu.

### CE's in Kits
To add Custom Enchantments and Items into kits, follow this guide:

- Check out if your kit plugin supports colored names and/or lores.
- Find example kits that add colored names and/or lores in your kit plugin
- For items, set "name: <Item>", for Enchantments, set "lore: <Enchantment>". You may have to find out how to add multiple lines of lore via your kit plugin

### Contributions
If you want to contribute to Custom Enchantments PE, please let me know at ztechnetwork.inc@gmail.com

Current Version: 1.0.0-beta
### Changelog
None(Still in development)
