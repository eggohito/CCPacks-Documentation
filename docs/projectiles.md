# Projectiles

### Fields

   Field   | Type | Default | Description
-----------|------|---------|-------------
`identifier` | [Identifier]() | *mandatory* | The identifier of what the projectile appears as in the /summon command, also used to reference it in the "apoli:fire_projectile" power type.
`base_item` | [Item]() | *mandatory* | What item the projectile looks like.
`damage` | [Int]() | 0 | How much damage the projectile does.
`damage_source` | [Damage Source]() | *mandatory* | What type of damage the projectile does.
`height` | [Float]() | 0.25 | Height of the projectile.
`width` | [Float]() | 0.25 | Width of the projectile.

### Example Code
```json
{
  "type": "ccpacks:projectile",
  "identifier": "ccpacks:magic_blast",
  "base_item": "minecraft:diamond_sword",
  "damage": 15,
  "damage_source": {
    "name": "freeze"
  },
  "height": 0.5,
  "width": 0.5
}
