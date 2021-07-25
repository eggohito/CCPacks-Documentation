### Raycast Block

This action gets the block you are looking at, with a limit to the distance (High distances may cause lag). You can then check what type of block it is, and do an action at the blocks location.

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
Opens the crafting GUI for the player
