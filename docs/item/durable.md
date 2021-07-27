# Custom Durable Items

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`subtype` | [String]() | *mandatory* | Defines the type of item.
`identifier` | [Identifier]() | *mandatory* | The identifier is what the item appears as in the /give command.
`durability` | [Integer]() | *mandatory* | How many uses the item has.
`lore` | [String [array]]() | *optional* | Lines of text below an item.

### Example Code

```json
{
    "type": "ccpacks:item",
    "subtype": "durable",
    "identifier": "example_pack:goat_horn",
    "durability": 50
}
```
