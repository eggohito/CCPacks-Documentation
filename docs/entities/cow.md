# Custom Cow

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandatory* | The identifier is what the item appears as in the /give command.
`texture` | [String]() | *mandatory* | The location for the texture in the assets folder.
`back_item` | [Item]() | *mandatory* | The item on the back of the cow (mushrooms on a mooshroom)

### Example Code

```json
{
	"type": "ccpacks:animal_entity",
	"subtype": "cow",
	"identifier": "example_pack:cow",
	"texture": "minecraft:textures/entity/cow/cow.png",
	"back_item": "minecraft:torch"
}
```
