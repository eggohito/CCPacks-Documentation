---
title: Apoli JSON
date: 2021-04-05
---
# Apoli JSON Format

This is the format of a JSON file describing an apoli. They need to be placed inside the `apolis` folder within your namespace.

### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`powers` | [Array](data_types/array.md) of [Identifiers](data_types/identifier.md) | _optional_ | IDs of the powers this apoli should have.
`icon` | [Item Stack](data_types/item_stack.md) | _optional_ | The item stack which is displayed as the icon for the apoli in the top-left corner of the choose/view apoli screen.
`unchoosable` | [Boolean](data_types/boolean.md) | false | If set to true, this apoli will not show up in any apoli layer to choose it, but it will still be able to be set for that layer with a command or via an apoli upgrade.
`order` | [Integer](data_types/integer.md) | _optional_ | Specifies the position of this apoli in the choose apoli screen among the other apolis with the same impact in the layer. If not specified, will be a really large number - basically adding it in the end.
`impact` | [Integer](data_types/integer.md) | 0 | Specifies the impact of this apoli with a number from 0 (none) to 3 (high).
`name` | [String](data_types/string.md) | _optional_ | The display name of the apoli. Can be a translation key which is localized in a language file, or the literal display name.
`description` | [String](data_types/string.md) | _optional_ | The description of the apoli. Can be a translation key which is localized in a language file, or the literal description.
`upgrades` | [Array](data_types/array.md) of [Upgrades](upgrade_json.md) | _optional_ | A list of upgrades for this apoli, specifying which advancements turn this apoli into which other apoli.
`loading_priority` | [Integer](data_types/integer.md) | 0 | Specifies when this apoli is loaded. Higher numbers mean it's loaded later, which means it will override those with lower loading priorities which share the same ID.
