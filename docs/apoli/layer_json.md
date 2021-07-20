---
title: Layer JSON
date: 2021-04-05
---
# Layer JSON Format

This is the format of a JSON file describing a layer. Layers are collections of apolis, and a player can have a single apoli on each layer. For example, the classes from the Apolis: Classes add-on are on a separate layer, thus you can choose a class _in addition to_ choosing an apoli.

Layer files need to be placed inside the `apoli_layers` folder within your namespace.

The most common use is to create a layer file at `data/apolis/apoli_layers/apoli.json` with `replace` set to false, in order to add a custom apoli to the list. See the examples below for what that would look like.

### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`order` | [Integer](data_types/integer.md) | _optional_ | Specifies the order of this layer in the choose and view apoli screen among the other layers. Smaller numbers mean it appears before layers with larger numbers.
`apolis` | [Array](data_types/array.md) of [Identifiers](data_types/identifier.md) and [Conditioned Apolis](conditioned_apolis.md) | | Defines the apolis that should be in this layer. [Identifier](data_types/identifier.md) strings and [Conditioned Apoli](conditioned_apolis.md) objects can be mixed in the same array.
`enabled` | [Boolean](data_types/boolean.md) | true | If set to false, this layer will be unavailable.
`replace` | [Boolean](data_types/boolean.md) | false | If set to false, the data in this file will be appended to an already existing version of this layer. Useful to add custom apolis to the default apoli layer for example. If set to true, the layer will be replaced and only the apolis specified in this file will appear.
`name` | [String](data_types/string.md) | _optional_ | The display name of the layer. Will show at the top of the GUI saying "Choose your [name here]". Can be a literal string or a translation key.
`missing_name` | [String](data_types/string.md) | _optional_ | The display name of the apoli that will show when viewing the apoli if no apoli has been assigned to this layer. Can be a literal string or a translation key.
`missing_description` | [String](data_types/string.md) | _optional_ | The description of the apoli that will show when viewing the apoli if no apoli has been assigned to this layer. Can be a literal string or a translation key.
`allow_random` | [Boolean](data_types/boolean.md) | false | If set to true, this layer will show an option for choosing a random apoli.
`allow_random_unchoosable` | [Boolean](data_types/boolean.md) | false | Whether apolis which are unchoosable (`unchoosable` field set to true in the apoli file) should be included in the random option. Can for example be used to force players to choose a random apoli, by setting this to true and making all apolis in the layer unchoosable.
`exclude_random` | [Array](data_types/array.md) of [Identifiers](data_types/identifier.md) | _optional_ | If specified, the apolis included in this list will not be picked by the random choice.
`default_apoli` | [Identifiers](data_types/identifier.md) | _optional_ | If set, the apoli with this ID will automatically be chosen for a new player. If an orb of apoli is used later on, the player will be able to choose another apoli then and the `default_apoli` will not apply. Could for example be used to make all players start as human, and then use the orb as a progression item to select an apoli.
`auto_choose` | [Boolean](data_types/boolean.md) | false | If set to true, this layer will automatically pick an apoli for the player if only one option is available. This also applies when an orb of apoli is used.
