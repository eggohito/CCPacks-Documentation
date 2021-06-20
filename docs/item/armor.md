# Custom Armor

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`name` | [String]() | *mandetory* | The name of the image files used to texture the armor.
`durability` | [Integer]() | *10* | How many uses the item has.
`protection` | [Integer]() | *0* | the amount of damage that a weapon does.
`knockback_resistance` | [Integer]() | *0* | How fast you can swing the weapon.
`enchantability` | [Integer]() | *0* | How likely you are to get good enchantments.
`lore` | [String [array]]() | *optional* | Lines of text below an item.
`powers` | [Power [array]]() | *optional* | The powers you are given when holding the item.

### Armor json structure

```json
{
	"type": "ccpacks:chestplate",
	"identifier": "example_pack:example_chestplate",
	"name": "example",
	"durability": 47,
	"protection": 4,
	"enchantability": 2,
	"toughness": 3,
	"knockback_resistance": 1,
	"powers": [
		"example_pack:elytra_power"
	],
	"lore": [
		"Hmmm, whats this?",
		"Looks like a powerful item"
	]
}
```
