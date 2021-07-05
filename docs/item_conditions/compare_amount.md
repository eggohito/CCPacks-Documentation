### Compare Amount

Checks the amount of an item stack.

### Fields:

Field  | Type | Default | Description
-------|------|---------|-------------
`comparison` | [Comparison]() | |  In what way to compare the durability the specified value.
`compare_to` | [Integer]() | | The value to compare durability against.

### Example
```json
"item_condition": {
    "type": "ccpacks:compare_amount",
    "comparison": ">",
    "compare_to": 4
}
```
Checks if the item stack has more than 4 items in it.