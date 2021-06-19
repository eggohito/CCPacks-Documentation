# Custom Durable Items

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`durability` | [Integer]() | *mandetory* | How many uses the item has.
`lore` | [String [array]]() | *optional* | Lines of text below an item.
`powers` | [Power [array]]() | *optional* | The powers you are given when holding the item.

### Example Code

```json
{
	"type": "ccpacks:durable_item",
	"identifier": "example_pack:emerald_star",
	"durability": 100,
	"powers": [
		"example_pack:elytra_power"
	],
	"lore": [
		"Hmmm, whats this?",
		"Looks like a powerful item"
	]
}
```
