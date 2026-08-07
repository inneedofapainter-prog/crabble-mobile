# Multi-select Move Update

Adds board tile multi-select so players can highlight multiple placed tiles or a whole word and move the selection together.

## Included

- Tap placed board tiles to select/highlight multiple letters.
- Tap **Word** after selecting one tile to select the whole word it belongs to.
- Tap an empty board cell to move the selected group in one shot while preserving shape.
- Recall one or many selected board tiles back to the rack.
- Clear selection button.
- Online server enforcement for group move/recall actions.
- How to Play text updated.

## Rule

The selected group moves by using its top-left selected tile as the anchor. The destination cell becomes the new top-left position. The move is rejected if it would land on any unselected occupied tile.
