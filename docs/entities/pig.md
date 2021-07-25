# Custom Pig

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandatory* | The identifier is what the item appears as in the /give command.
`texture` | [String]() | *mandatory* | The location for the texture in the assets folder.

### Example Code

```json
{
	"type": "ccpacks:animal_entity",
	"subtype": "pig",
	"identifier": "example_pack:pig",
	"texture": "minecraft:textures/entity/pig.png"
}
```
