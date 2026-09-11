---
description: Pre-publish check on a content folder
argument-hint: <content-folder-name>
---

Check everything in `content/$1/` against `content/$1/brand-pack-snapshot.md`
and write findings to `content/$1/qa.md`. Report problems; fix nothing silently.

- **Model integrity:** does any copy imply Sanguine delivers the service rather
  than connecting parties? Quote every instance. Top failure mode.
- **Naming:** every service and entity name matched against the snapshot's
  coverage map.
- **Claims:** every factual claim has a working source link.
- **Proof:** every named client, number or outcome appears in the snapshot's
  approved list. Anything else is a blocker.
- **Compliance:** every flagged claim marked and routed to the named signatory.
- **Voice:** flag anything templated, hedged, or failing the two-sentence test.
  Quote it.
- **Links and UTMs:** all links resolve; UTMs present, consistent, well formed.
- **Derivation:** every channel variant traces to a claim in `source.md`.
- **Drift check:** fetch the live Notion pack and diff it against the snapshot.
  If the rules changed mid-production, say what changed — the piece may need
  rework before it ships.

End with one verdict line: `PASS`, `PASS WITH FLAGS`, or `BLOCKED`.
