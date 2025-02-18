---
title: Shader (Power Type)
date: 2021-07-13
---
# Shader

[Power Type](../power_types.md).

Applies a shader effect to the player's vision.

Type ID: `origins:shader`

### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`shader` | [Identifier](../data_types/identifier.md) | | Specifies the location of the shader resource file to use. For more information about shaders, look at [Minecraft Wiki: Shaders (Before 1.9)](https://minecraft.fandom.com/wiki/Shaders/Before_1.9).

### Example
```json
{
  	"type": "origins:shader",
  	"shader": "minecraft:shaders/post/pencil.json"
}
```
This makes the player view the world as a pencil sketch!
