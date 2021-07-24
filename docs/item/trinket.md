# Custom Trinkets

Custom Trinkets requires the [Trinkets](https://www.curseforge.com/minecraft/mc-mods/trinkets-fabric) mod in order to function. There is a [wiki for Trinkets](https://github.com/emilyalexandra/trinkets/wiki) that will help with getting trinkets set up.

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`durability` | [Integer]() | *mandetory* | How many uses the item has.

### Example Code

```json
{
	"type": "ccpacks:item",
    "subtype": "trinket",
	"identifier": "example_pack:elytra_trinket",
	"durability": 100
}
```
