# Custom Durable Items

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`durability` | [Integer]() | *mandetory* | How many uses the item has.
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
