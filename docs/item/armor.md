---
title: Armor
date: 2021-06-03
---

# Armor json structure

.. list-table:: Title
   :widths: 25 25 50
   :header-rows: 1

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 1, column 1
     -
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3

+------+---------------+
| Field |  Description |
+======+===============+
| type | This defines what item you would be creating |
+------+---------------+
| identifier | This is what you would enter when you do [/give @s (identifier)] |
+------+---------------+

```json
{
	"type": "ccpacks:chestplate",
	"identifier": "example_pack:example_chestplate",
	"name": "example",
	"durability": 47,
	"protection": 4,
	"enchantability": 2,
	"toughness": 3,
	"knockback_resistance": 1,
	"powers": [
		"example_pack:elytra power"
	],
	"lore": [
		"Hmmm, whats this?",
		"Looks like a powerful item"
	]
}
```
