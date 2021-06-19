# Custom Weapons

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`durability` | [Integer]() | *10* | How many uses the item has.
`mining_speed_multiplier` | [Float]() | *0* | (unknown, if you know, tell me on the discord)
`attack_damage` | [Integer]() | *0* | the amount of damage that a weapon does.
`attack_speed` | [Integer]() | *0* | How fast you can swing the weapon.
`mining_level` | [Integer]() | *optional* | doesn't actually do anything on swords.
`enchantability` | [Integer]() | *0* | How likely you are to get good enchantments.
`lore` | [String [array]]() | *optional* | Lines of text below an item.
`powers` | [Power [array]]() | *optional* | The powers you are given when holding the item.

### Example Code

```json
{
	"type": "ccpacks:sword",
	"identifier": "example_pack:example_sword",
	"durability": 47,
	"mining_speed_multiplier": 0,
	"attack_damage": 9,
	"attack_speed": 2.7,
	"mining_level": 0,
	"enchantability": 7,
	"lore": [
		"first line of lore",
		"second line of lore"
	],
	"powers": [
		"origins:fall_immunity"
	]
}
```
