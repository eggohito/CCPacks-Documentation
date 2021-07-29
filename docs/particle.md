# Particles

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandatory* | The identifier is what the particle appears as in the /particle command.
`max_age` | [Int]() | 100 | How many ticks the particle lasts for.
`size` | [Float]() | 0.25 | The scale of the particle in relation to a block. Set it to 1 to make the size equal to a full block.
`collides_with_world` | [Bool]() | false | Whether the particle collides with the world or not.
`red` | [Float]() | *optional* | The red value of the particle. If the red, green and blue values are all unset, the colour will default to those on the texture.
`green` | [Float]() | *optional* | The green value of the particle.
`blue` | [Float]() | *optional* | The blue value of the particle.
`alpha` | [Float]() | 1 | Opacity of the particle. 0 is transparent, 1 is opaque.
`glowing` | [Bool]() | false | Whether the particle glows or not.

### Example Code

```json
{
  "type": "ccpacks:particle",
  "identifier": "example_pack:butterfly",
  "max_age": 10,
  "size": 0.1,
  "collides_with_world": true,
  "red": 50,
  "green": 168,
  "blue": 82,
  "alpha": 0.2,
  "glowing": true
}
```
