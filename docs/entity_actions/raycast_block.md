### Raycast Block

This action gets the block you are looking at, with a limit to the distance (High distances may cause lag). You can then check what type of block it is, and do an action at the blocks location.

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`distance` | [Int]() | *mandetory* | The distance that the ray travels
`entity_action` | [Entity Action]() | *optional* | The entity action that is run.
`block_action` | [Block Action]() | *optional* | The block action that is run.
`block_condition` | [Block Condition]() | *optional* | The condition that checks the block that the ray hits.



### Example
```json
"entity_action": {
  	"type": "ccpacks:raycast_block",
	"distance": 5,
	"entity_action": {
		"type": "origins:heal",
		"amount": 6
	},
	"block_condition": {
		"type": "apoli:block",
		"block": "example_pack:health_block"
	}
}
```
Heals the player by 3 hearts when you right click the health block.
