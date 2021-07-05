# Falling Block

Falling blocks are identical to generic blocks, but they are affected by gravity.

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`sound` | [Sound]() | *1* | The sound the block makes when broken.
`material` | [Material]() | *optional* | The sounds related to the player moving and walking on the block.
`effective_tool` | [Effective Tool]() | *optional* | The tool you need to use to mine the block.
`mining_level` | [Integer]() | *optional* | What mining level you have to be in order to break the block.
`hardness` | [Integer]() | *3* | How long it takes to break (3 is stone 50 is obsidian).
`slipperiness` | [Float]() | *0.6f* | 
`resistance` | [Integer]() | *3* | How immune to explosions the block is (3 is stone, 1500 is obsidian).
`luminance` | [Integer]() | *0* | The light level that the block gives off
`action` | [Entity Action]() | *optional* | Runs the action on the player when they right click the block

### Example Code

```json
{
    "type": "ccpacks:falling_block",
    "identifier": "example_pack:health_block",
    "sound": "glass",
    "material": "stone",
    "effective_tool": "pickaxe",
    "mining_level": 2,
    "hardness": 3,
    "slipperiness": 0.6,
    "resistance": 3,
    "luminance": 15,
	"loot_table": "example_pack:data",
    "action": {
        "type": "apoli:heal",
		"amount": 6
    }
}
```