# Custom Weapons

### Fields:

Field  | Type | Default | Description
-------|------|---------|-------------
add("identifier", SerializableDataTypes.IDENTIFIER)
            .add("", SerializableDataTypes.INT, 64)
            .add("",SerializableDataTypes.INT, 4)
            .add("",SerializableDataTypes.FLOAT, 8f)
            .add("",SerializableDataTypes.BOOLEAN, false)
            .add("",SerializableDataTypes.BOOLEAN, false)
            .add("lore", CCPackDataTypes.STRINGS, null)
            .add("",SerializableDataTypes.BOOLEAN, false);
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`max_count` | [Integer]() | *64* | How many of the item you can have in one stack.
`hunger` | [Integer]() | *4* | how many hunger it fills up (1 = half a bar)
`saturation` | [Float]() | *8f* | How many saturation points the food fills
`meat` | [Boolean]() | *false* | Can it be fed to dogs?
`always_edible` | [Boolean]() | *false* | Can you eat it even when full?
`snack` | [Boolean]() | *false* | If true, makes it so you eat it fast, like dried kelp.
`lore` | [String [array]]() | *optional* | Filler

### Example Code:

```json
{
	"type": "ccpacks:food",
	"identifier": "example_pack:emerald_food",
	"max_count": 47,
	"hunger": 8,
	"saturation": 12,
	"meat": false,
	"always_edible": true,
	"snack": true,
	"lore": [
		"Line of lore text"
	]
}
```
