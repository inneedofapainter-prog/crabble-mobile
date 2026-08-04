# Word Policy Update

This update tightens Crabble word validation by blocking a curated list of abbreviated words, chat/text shorthand, and slang-style entries while still allowing valid two-letter dictionary words.

## Included

- Common chat abbreviations such as `lol`, `brb`, `btw`, `omg`, `idk`, `tbh`, `fyi`, etc.
- Common slang-style words such as `bro`, `bruh`, `fam`, `sus`, `yeet`, `noob`, etc.
- Common shortened forms such as `app`, `info`, `pic`, `promo`, `demo`, `stats`, `vid`, etc.
- Server-side validation, mobile-web validation, GO validation, and dump-tile helper validation all use the same policy.

## Notes

Valid two-letter words remain allowed. If another non-standard word slips through, add it to `BANNED_ABBREVIATED_OR_SLANG_WORDS` in the dictionary policy and redeploy.
