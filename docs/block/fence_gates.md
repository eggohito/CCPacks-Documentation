# Fence Gate

A fence gate is an interactable block with a shape similar to fences. Can switch between an open and closed state by right-clicking. (`key.use` keybind)

`type` ID: `"ccpacks:block"`

`subtype` ID: `"fence_gate"`


### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandatory* | The identifier is what the item appears as in the /give command.
`sound` | [Sound](properties/sounds.md) | *`"bone"`* | The sound the block makes when broken.
`material` | [Material](properties/materials.md) | *`"stone"`* | The sounds related to the player moving and walking on the block.
`effective_tool` | [Effective Tool]() | *optional* | The tool you need to use to mine the block.
`collidable` | [Boolean]() | *`true`* | Determines if the block has a collision box.
`transparent` | [Boolean]() | *`false`* | Determines if the block is transparent.
`mining_level` | [Integer]() | *`1`* | What mining level you have to be in order to break the block.
`hardness` | [Integer]() | *`3`* | How long it takes to break (3 is stone 50 is obsidian).
`slipperiness` | [Float]() | *`0.6`* | How slippery the block is; lower = more slippery, higher = less slippery 
`resistance` | [Integer]() | *`3`* | How resistant to explosions the block is (3 is stone, 1500 is obsidian).
`luminance` | [Integer]() | *`0`* | The light level that the block gives off
`make_block_item` | [Boolean]() | *`true`* | If false, makes it so it does not register a block item.
`loot_table` | [Loot Table]() | *mandatory* | The loot table for the block(s) that is dropped when this block is broken

### Example Code

```json
{
    "type": "ccpacks:block",
	"subtype": "fence_gate",
    "identifier": "example_pack:bone_fence_gate",
    "sound": "glass",
    "material": "stone",
    "effective_tool": "pickaxe",
    "mining_level": 2,
    "hardness": 3,
    "slipperiness": 0.6,
    "resistance": 3,
    "luminance": 15,
	"loot_table": "example_pack:data"
}
```

This example creates a fence gate block that sounds like glass when broken, and stone when being stepped on. It also has the same hardness and blast resistance of a stone block.