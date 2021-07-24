# Custom Food

### Fields:

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`max_count` | [Integer]() | *64* | How many of the item you can have in one stack.
`hunger` | [Integer]() | *4* | how many hunger it fills up (1 = half a bar)
`saturation` | [Float]() | *8f* | How many saturation points the food fills
`meat` | [Boolean]() | *false* | Can it be fed to dogs?
`always_edible` | [Boolean]() | *false* | Can you eat it even when full?
`snack` | [Boolean]() | *false* | If true, makes it so you eat it fast, like dried kelp.
`lore` | [String [array]]() | *optional* | Lines of text below an item.

### Example Code:

```json
{
    "type": "ccpacks:item",
    "subtype": "food",
    "identifier": "example_pack:glitter_food",
    "max_count": 64,
    "hunger": 8,
    "saturation": 12,
    "meat": false,
    "always_edible": true,
    "snack": true,
    "lore": [
        "Some say you should never eat this...",
		"They are WRONG."
    ]
}
```
