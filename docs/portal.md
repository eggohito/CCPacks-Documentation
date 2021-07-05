# Dimention Portals

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`block` | [Identifier]() | *mandetory* | The block that the portal is made out of.
`ignition_item` | [Identifier]() | *mandetory* | The Item used to ignite the portal with.
`dimension` | [Identifier]() | *mandetory* | The dimention that the portal takes you to.
`red` | [Int]() | *optional* | The red value of the portal.
`green` | [Int]() | *optional* | The green value of the portal.
`blue` | [Int]() | *optional* | The blue value of the portal.

### Example Code

```json
{
	"type": "ccpacks:portal",
	"block": "minecraft:end_stone",
	"ignition_item": "minecraft:heart_of_the_sea",
	"dimention": "minecraft:the_end",
	"red": 37,
	"green": 25,
	"blue": 51
}
```
