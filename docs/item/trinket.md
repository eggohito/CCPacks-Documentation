# Custom Trinkets

Custom Trinkets requires the [Trinkets](https://www.curseforge.com/minecraft/mc-mods/trinkets-fabric) mod in order to function. There is a [wiki for Trinkets](https://github.com/emilyalexandra/trinkets/wiki) that will help with getting trinkets set up.

### Fields

    Field    | Type | Default | Description
-------------|------|---------|-------------
`identifier`   | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`powers`   | [Power [array]]() | *optional* | The powers you are given when the item is in its trinket slot.

### Example Code

```json
{
	"type": "ccpacks:trinket",
	"identifier": "example_pack:elytra_trinket",
	"powers": [
		"example_pack:elytra_flight"
	]
}
```
