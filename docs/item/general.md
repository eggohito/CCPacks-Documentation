# Custom Items

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`max_count` | [Integer]() | *1* | How many uses the item has.
`lore` | [String [array]]() | *optional* | Lines of text below an item.
`powers` | [Power [array]]() | *optional* | The powers you are given when holding the item.

### Example Code

```json
{
	"type": "ccpacks:item",
	"identifier": "example_pack:example_star",
	"max_count": 1,
	"lore": [
		"a star that shines like a hundred suns"
	],
	"powers": [
		"example_pack:elytra_power"
	]	
}
```
