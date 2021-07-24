# Custom Disc



### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`powers` | [Power [array]]() | *optional* | The powers you are given when the item is in its trinket slot.

### Example Code

```json
{
    "type": "ccpacks:item",
    "subtype": "music_disc",
    "identifier": "example_pack:music_disc_tall",
    "comparator_output": 15,
    "sound": "example_pack:music_disc_tall"
}
```
