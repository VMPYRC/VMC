# Datapack Changes

- Added a bunch of new recipes for
  - Smelting (Furnace)
  - Crafting (Crafting Table)

## Smelting (Furnace)

|      Input       |    Output    |
| :--------------: | :----------: |
| Raw Copper Block | Copper Block |
|  Raw Gold Block  |  Gold Block  |
|  Raw Iron Block  |  Iron Block  |
|   Rotten Flesh   |   Leather    |

## Crafting (Crafting Table)

- `Input` = the items you put into the crafting table
- `Output` = the crafted items you receive
- `Recycle` = `Output` items that can convert back to the original `Input` materials
- `Vanilla` = Recipe available in Vanilla
- Plural items are listed as singular
  - 5 Iron Ingots -> 5 Iron Ingot

### Armor for Animals

| Input                         | Output                  | Recycle           |
| ----------------------------- | :---------------------- | :---------------- |
| `Vanilla`                     | 1 Leather Horse Armor   | 7 Leather         |
| 5 Copper Ingot<br>1 Saddle    | 1 Copper Horse Armor    | 5 Copper Ingot    |
| 5 Iron Ingot<br>1 Saddle      | 1 Iron Horse Armor      | 5 Iron Ingot      |
| 5 Gold Ingot<br>1 Saddle      | 1 Golden Horse Armor    | 5 Gold Ingot      |
| 5 Diamond<br>1 Saddle         | 1 Diamond Horse Armor   | 5 Diamond         |
| 5 Netherite Ingot<br>1 Saddle | 1 Netherite Horse Armor | 5 Netherite Ingot |
| `Vanilla`                     | 1 Saddle                | 3 Leather         |
| `Vanilla`                     | 1 Wolf Armor            | 6 Armadillo Scute |

### Armor for Players

- Armor can be crafted back into their original material
- Conversions
  - 5 = Helmet
  - 8 = Chestplate
  - 7 = Leggings
  - 4 = Boots
- Armor
  - Copper Armor = Copper Ingot
  - Iron Armor = Iron Ingot
  - Golden Armor = Gold Ingot
  - Chainmail Armor = Chain (Recycle included)
  - Diamond Armor = Diamond
- 1 Turtle Helmet = 5 Turtle Scute

### Tools

- Tools can be crafted back into their original material
- Examples
  - Diamond Axe = 3 Diamond
  - Wooden Axe = 8 Stick
    - Wooden Axe = 3 Plank, 2 Stick
    - 2 Plank = 4 Stick (Vanilla Recipe)
    - 1 Plank = 2 Stick (Assumed Ratio)
    - 3 Plank = 6 Stick
    - 6 Stick + 2 Stick = 8 Stick Total
- Conversions
  - 3 = Axe
  - 2 = Hoe
  - 3 = Pickaxe
  - 1 = Shovel
  - 2 = Sword
- Tools
  - Wooden Tools = Sticks (See example above)
  - Stone Tools = Cobblestone
  - Copper Tools = Copper Ingot
  - Iron Tools = Iron Ingot
  - Golden Tools = Gold Ingot
  - Diamond Tools = Diamond
- 1 Flint and Steel = 1 Iron Ingot

### Beds

| Input | Output |     Recycle      |
| :---: | :----: | :--------------: |
| 1 Bed | 3 Wool | `Vanilla`, Input |

- Black
- Blue
- Brown
- Cyan
- Gray
- Green
- Light Blue
- Light Gray
- Lime
- Magenta
- Orange
- Pink
- Purple
- Red
- White
- Yellow

### Block Conversions (Shapeless)

| Input             | Output           |     Recycle      |
| :---------------- | :--------------- | :--------------: |
| 1 Amethyst Block  | 4 Amethyst Shard | `Vanilla`, Input |
| 1 Bricks (Block)  | 4 Brick          | `Vanilla`, Input |
| 1 Clay (Block)    | 4 Clay Ball      | `Vanilla`, Input |
| 1 Glowstone       | 4 Glowstone Dust | `Vanilla`, Input |
| 1 Honeycomb Block | 4 Honeycomb      | `Vanilla`, Input |
| 1 Magma Block     | 4 Magma Cream    | `Vanilla`, Input |
| 1 Melon           | 9 Melon Slice    | `Vanilla`, Input |
| 1 Nether Bricks   | 4 Nether Brick   | `Vanilla`, Input |
| 1 Block of Quartz | 4 Nether Quartz  | `Vanilla`, Input |

#### Snow / Ice

| Input        |    Output    |     Recycle      |
| :----------- | :----------: | :--------------: |
| 1 Snow Block |  4 Snowball  | `Vanilla`, Input |
| 1 Blue Ice   | 9 Packed Ice | `Vanilla`, Input |
| 1 Packed Ice |    9 Ice     | `Vanilla`, Input |

### Dirt

| Input                            |      Output      |
| :------------------------------- | :--------------: |
| 1 Wheat Seed<br>1 Dirt Block     |  1 Grass Block   |
| 4 Hanging Root<br>1 Dirt Block   |  1 Rooted Dirt   |
| 1 Brown Mushroom<br>1 Dirt Block |    1 Mycelium    |
| 1 Red Mushroom<br>1 Dirt Block   |    1 Mycelium    |
| 1 Crimson Fungus<br>1 Dirt Block | 1 Crimson Nylium |
| 1 Warped Fungus<br>1 Dirt Block  | 1 Warped Nylium  |

### Dyes

| Input                                       |   Output    |
| :------------------------------------------ | :---------: |
| 1 Charcoal                                  | 1 Black Dye |
| 1 Coal                                      | 1 Black Dye |
| 1 Red Dye<br>1 Yellow Dye<br>1 Blue Dye<br> | 3 Brown Dye |
| 1 Yellow Dye<br>1 Blue Dye<br>              | 2 Green Dye |

### Fungi

| Input               |         Output         |     Recycle      |
| :------------------ | :--------------------: | :--------------: |
| 4 Brown Mushroom    | 1 Brown Mushroom Block |      Input       |
| 4 Red Mushroom      |  1 Red Mushroom Block  |      Input       |
| 1 Nether Wart Block |     9 Nether Wart      | `Vanilla`, Input |

### Minecart + Rails

- Note on the Rail recipe:
  - Original Recipe to create Rail
    - 6 Iron Ingot + 1 Stick = 16 Rail
  - If divided by 2... 3 Iron Ingot = 8 Rail

| Input                   |    Output     |     Recycle      |
| :---------------------- | :-----------: | :--------------: |
| 8 Rail                  | 3 Iron Ingot  |  See Note Above  |
| 1 Minecart              | 5 Iron Ingot  | `Vanilla`, Input |
| 1 Minecart with Hopper  | 10 Iron Ingot |    `Vanilla`     |
| 1 Minecart with Chest   |  1 Minecart   |    `Vanilla`     |
| 1 Minecart with Furnace |  1 Minecart   |    `Vanilla`     |

### Music Discs

- 2 Music Disc = 1 Music Disc (Next)
- Example: 2 Music Disc (13) = 1 Music Disc (cat)
- Based on track order

1. 13
2. cat
3. blocks
4. chirp
5. far
6. mall
7. mellohi
8. stal
9. strad
10. ward
11. 11
12. wait
13. otherside
14. 5
15. Pigstep
16. Relic
17. Creator
18. Creator (Music Box)
19. Precipice
20. Tears

### Ocean / Aquatic

| Input                                                            |       Output       |
| :--------------------------------------------------------------- | :----------------: |
| 4 Prismarine Shard<br>5 Prismarine Crystals<br>1 Diamond         | 1 Heart of the Sea |
| 1 Prismarine Shard<br>3 Prismarine Crystal<br>1 Heart of the Sea |     1 Trident      |

### Powerful / Endgame

| Input                                                                                  |          Output          |
| :------------------------------------------------------------------------------------- | :----------------------: |
| 1 End Rod<br>1 Nether Star<br>6 Phantom Membrane                                       |         1 Elytra         |
| 8 Gold Block<br>1 Golden Apple                                                         | 1 Enchanted Golden Apple |
| 2 Emerald Block<br>1 Eye of Ender<br>3 Gold Block<br>1 Diamond Block<br>2 Blaze Powder |    1 Totem of Undying    |

### Uncategorized

| Input                                               | Output              |     Recycle      |
| :-------------------------------------------------- | :------------------ | :--------------: |
| 1 Lava Bucket<br>1 Water Bucket                     | 1 Obsidian          |                  |
| 1 Ghast Tear<br>8 Obsidian                          | 8 Crying Obsidian   |                  |
| 1 Blackstone<br>4 Gold Nugget                       | 1 Gilded Blackstone |                  |
| 1 String<br>2 Paper                                 | 1 Name Tag          |                  |
| 1 Stick<br>6 Stone<br>1 Gold Ingot<br>1 Gold Nugget | 1 Bell              |                  |
| 1 Beetroot Soup                                     | 1 Bowl              |                  |
| 1 Rabbit Stew                                       | 1 Bowl              |                  |
| 3 Bone Meal                                         | 1 Bone              | `Vanilla`, Input |
| 9 Gravel                                            | 1 Flint             |                  |
| 1 Filled Map                                        | 1 Map (Empty)       |                  |
| 9 String                                            | 1 Cobweb            |      Input       |
| 1 Rabbit Hide<br>1 String                           | 1 Bundle            |                  |
| 1 Honey Block<br>1 Piston                           | 1 Sticky Piston     |                  |
