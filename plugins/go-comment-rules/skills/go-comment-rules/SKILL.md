---
name: go-comment-rules
description: Rules for writing or editing comments in Go code. Use whenever adding, changing or reviewing comments in .go files.
---

# Go comment rules

Default: no comment. Comment only what the code cannot say.

- **Do**: why (reason, constraint, firmware/ticket reference), surprising code, exported names.
- **Don't**: restate code or name, change history ("now uses X", "fixed Y"), obvious behavior, every parameter.
- **Declarations (exported and unexported)**: doc comment starting with the name, full sentence, ends with a period. Required on exported names only.
- **In-body, end-of-line**: no format rule, follow the file's style.
- **Language**: write comments in ASD-STE100 Simplified Technical English.
- **No em dashes**: write the sentence again with a colon, commas or parentheses, or make two sentences.
- **Existing code**: don't touch comments out of scope; when fixing one, keep the original wording; remove stale ones.
