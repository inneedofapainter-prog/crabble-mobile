# Q Rule Fix

This update removes the old Q bypass for the GO button.

## Rule now

- Q must be played from the rack like every other tile.
- GO only unlocks when the player's hand is empty and the board is valid/connected.
- Valid Q words are still allowed, including valid two-letter words such as `QI`.
- If Q cannot make any valid word from the hand plus board, Dump Tile can unlock under the normal no-valid-word rule.
- Server-side validation also blocks forced GO calls with Q still in hand.

## Based on

Stable crash-fix package, keeping the stats tab, profile lobby, 3+ room flow, word policy, GI fix, rematch/winner fix, and share app updates.
