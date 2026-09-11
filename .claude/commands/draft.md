---
description: Draft the source piece from an approved brief
argument-hint: <content-folder-name>
---

1. Read `CLAUDE.md`, `content/$1/brief.md`, and `content/$1/brand-pack-snapshot.md`.
   **Use the snapshot, not Notion.** The pack may have changed since the brief
   was approved; the whole point of the snapshot is that it hasn't for this piece.
   If the snapshot is missing, stop — the brief was not produced properly.
2. If the brief is not marked APPROVED, stop and say so.
3. Write the source piece to `content/$1/source.md`.
4. Hold the brief's angle. If you think it's wrong, write your objection to
   `content/$1/objection.md` and still draft what was asked.
5. Every factual claim carries a link. No citation, no claim.
6. If any compliance-flagged claim survived into the draft, put
   `STATUS: NEEDS REVIEW` on line one and quote the claim beneath it.

The source piece is canonical. Every channel variant derives from it.
