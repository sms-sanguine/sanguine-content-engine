---
description: Audit brand pack readiness and refresh local fallback copies
argument-hint: [brand-slug — omit for all]
---

Normal runs fetch brand packs live from Notion. This command exists for two
other jobs: telling you which packs are ready to use, and keeping local copies
current for when Notion is unreachable.

1. Read `brands/_SOURCES.md`.
2. Fetch the parent Content Engine page and list its children. Report any child
   page not registered in `_SOURCES.md` — someone added a brand without telling
   the mapping.
3. For each brand in scope (all, or `$1`), fetch the Notion page and overwrite
   its local file, with this header:

   ```
   <!-- FALLBACK COPY — GENERATED FROM NOTION, DO NOT EDIT LOCALLY -->
   <!-- source: <notion url> | synced: <ISO timestamp> -->
   ```

4. Print a readiness table:

   | Brand | Coverage map | Audience | Approved proof | Compliance | Pillars |

   Mark each cell `filled`, `partial`, or `EMPTY`. A section is EMPTY if it
   holds template prompt text, is blank, or contains only `[?]` or `TBC`.

5. State plainly which brands are ready for `/brief` and which are not. Empty
   Coverage map or empty Approved proof means **not ready** — say so.

Read-only against Notion. The team edits there; the engine reads.
