---
description: Fan an approved source piece out into channel-native variants
argument-hint: <content-folder-name>
---

Read `content/$1/source.md` and the Channels section of
`content/$1/brand-pack-snapshot.md`. Do not fetch from Notion — this piece is
governed by its snapshot.

Produce `content/$1/distribution/`, one file per channel variant.

Rules:
- Derive from the source piece. No new research, no new claims.
- Each variant native to its channel, not the same text reflowed. A LinkedIn
  post is not the intro paragraph with line breaks.
- Carry compliance flags through. A flagged claim stays flagged everywhere.
- Build UTMs per the convention in `CLAUDE.md` and record them together in
  `distribution/utms.md` so nothing drifts.
- Default fan-out (adjust per the snapshot's Channels section):
  - `linkedin-organic.md` — 3 post variants, different hooks, same idea
  - `newsletter.md` — section-length treatment, single CTA
  - `sales-email.md` — for reps to send 1:1, not a broadcast
  - `social-static.md` — copy and art direction for 3 static assets
  - `paid-variants.md` — 5 headline/primary-text pairs for testing
