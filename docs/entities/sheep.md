# Custom Sheep

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandatory* | The identifier is what the item appears as in the /give command.
`texture` | [String]() | *mandatory* | The location for the texture in the assets folder.

### Example Code

```json
{
	"type": "ccpacks:animal_entity",
	"subtype": "sheep",
	"identifier": "example_pack:sheep",
	"texture": "minecraft:textures/entity/sheep.png"
}
```
