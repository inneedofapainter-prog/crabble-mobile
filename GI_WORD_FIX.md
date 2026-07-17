# GI word validation fix

Updated Crabble word validation so valid 2-letter words are still allowed, but `GI` is rejected.

## Changes

- Removed `gi` from the explicit valid 2-letter word list.
- Kept proper 2-letter words such as `go`, `in`, `it`, `as`, `we`, `qi`, and `za`.
- Updated dump-tile helper logic so the larger dictionary does not accidentally re-allow 2-letter words outside the approved list.
- Server-side validation and mobile-web validation are both updated.
