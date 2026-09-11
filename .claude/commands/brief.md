---
description: Turn a raw idea or keyword into an approved content brief
argument-hint: <brand-slug> "<topic or keyword>"
---

1. Read `CLAUDE.md` and `brands/_SOURCES.md`.
2. **Fetch the brand pack live from Notion** using the page ID for `$1` in
   `_SOURCES.md`. If Notion is unreachable, fall back to `brands/$1.md` and say
   clearly in your output that you used a local copy and when it was synced.
3. Check readiness. If the Coverage map or Approved proof sections are empty or
   still hold template prompt text, stop and report what's missing. Do not brief
   against an unfilled pack.
4. Create `content/<YYYY-MM-DD>-<slug>/` and write the pack you just fetched to
   `brand-pack-snapshot.md` inside it, with a header noting the Notion URL and
   fetch timestamp. **Every later step reads this snapshot, not Notion** — so the
   whole piece is produced against one fixed version of the rules.
5. Research the topic. Find what already ranks or gets cited and what the
   audience is actually asking. Note the gap we can own.
6. Write `brief.md` in that folder:
   - **Pillar** it ladders to
   - **Reader** and the trigger that brings them here
   - **The single idea** — two sentences, per house standard
   - **Why us** — what Sanguine can say here that a competitor cannot
   - **Proof to use** — only from the snapshot's approved list
   - **Search/AEO targets** — primary term, intent, difficulty if known
   - **Distribution plan** — which channels this fans out to and why
   - **Compliance flags** — anything in the snapshot that will need review
   - **What this is NOT** — the obvious angle we are deliberately not taking

Stop after the brief. A human approves it before `/draft` runs.
