---
title: Upgrade JSON
date: 2021-04-05
---
# Upgrade JSON Format

An [Object](data_types/object.md) used to specify an upgrade of an apoli within an [Apoli JSON](apoli_json.md).


### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`condition` | [Identifier](data_types/identifier.md) | | ID of an advancement which should trigger this upgrade.
`apoli` | [Identifier](data_types/identifier.md) | | ID of an apoli the apoli with this upgrade should upgrade to.
`announcement` | [String](data_types/string.md) | _optional_ | A text which will show up in the local chat of the player in a pretty color. If none is specified, there won't be a message.
