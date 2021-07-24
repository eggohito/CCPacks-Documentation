# Status Effects

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /effect command.
`red` | [Int]() | *optional* | The red value of the effect.
`green` | [Int]() | *optional* | The green value of the effect.
`blue` | [Int]() | *optional* | The blue value of the effect.

### Example Code

```json
{
	"type": "ccpacks:status_effect",
	"identifier": "example_pack:magic_effect",
	"red": 32,
	"green": 176,
	"blue": 189
}
```
