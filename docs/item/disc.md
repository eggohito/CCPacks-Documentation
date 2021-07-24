# Custom Disc



### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandetory* | The identifier is what the item appears as in the /give command.
`sound` | [Identifier]() | *mandetory* | the sound event that the disc uses.
`comparator_output` | [Int]() | *optional* | The signal strength a comparator outputs from this disc

### Example Code

```json
{
  "type": "ccpacks:item",
  "subtype": "music_disc",
  "identifier": "example_pack:funky_disc",
  "comparator_output": 8,
  "sound": "example_pack:funky_sound"
}
```
