# Custom Items

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`subtype` | [String]() | *mandatory* | Defines the type of item.
`identifier` | [Identifier]() | *mandatory* | The identifier is what the item appears as in the /give command.
`max_count` | [Integer]() | *1* | How many uses the item has.
`lore` | [String [array]]() | *optional* | Lines of text below an item.

### Example Code

```json
{
    "type": "ccpacks:item",
    "subtype": "generic",
    "identifier": "example_pack:amethyst_netherite_ingot",
    "max_count": 64
}
```
