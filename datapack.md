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
