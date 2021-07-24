# Custom Cow

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`texture` | [String]() | *mandetory* | The location for the texture in the assets folder.
`back_item` | [Item]() | *mandetory* | The item on the back of the cow (mushrooms on a mooshroom)

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
