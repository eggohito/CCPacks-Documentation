---
title: Conditioned Apoli JSON
date: 2021-04-05
---
# Upgrade JSON Format

An [Object](data_types/object.md) used to specify apolis in a [Layer JSON](layer_json.md) which only show up conditionally.

### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`condition` | [Entity Condition](entity_conditions.md) | | The condition that the player needs to fulfill to get access to the apolis specified here.
`apolis` | [Array](data_types/array.md) of [Identifiers](data_types/identifier.md) | | IDs of the apolis which should become available when the `condition` is fulfilled.
