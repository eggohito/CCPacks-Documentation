# Status Effects

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`powers` | [Power [array]]() | *optional* | The powers you are given when the player has the effect.

### Example Code

```json
{
	"type": "ccpacks:status_effect",
	"identifier": "example_pack:creeper_friend",
	"powers": [
		"example_pack:neutral_mobs"
	]
}
```
