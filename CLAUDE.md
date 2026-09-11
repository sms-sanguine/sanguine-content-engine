# Sanguine Content Engine — operating rules

You are producing marketing content for Sanguine. Read this file plus the
relevant brand pack in `brands/` before writing anything.

## What Sanguine is

Sanguine does not deliver the underlying work. It connects parties and takes a
clip of the ticket. Biz Head Law does not practise law — it brings in matters
and connects them to co-counsel. Sanguine Legal Solutions connects firms to
service providers. Preventative Health and Tax Mitigation follow the same
broker model.

**This changes the copy.** Never write as though Sanguine performs the service.
The value proposition is access, matching, and vetting — not delivery. Getting
this wrong is the single most common failure mode in drafts. Check every claim
against it.

## House copy standard

- Concise, direct, authoritative. No hedging, no throat-clearing.
- Lead with the benefit, not the mechanism.
- The two-sentence rule: any core proposition must survive being stated in two
  sentences. If it needs a paragraph, it isn't clear yet.
- Write plainly. Avoid em-dash asides, "not X but Y" constructions, rhetorical
  questions as openers, and stock phrases ("in today's landscape", "unlock",
  "leverage", "game-changing", "it's worth noting").
- Assume the reader is a busy professional who will leave. Earn the next line.

## Anti-template rule

Output that reads as templated is a failure even if it is accurate. Specific
beats generic every time: a named scenario, a real number, a concrete
consequence. If a sentence could appear on a competitor's site with the brand
name swapped, rewrite it.

## Naming discipline

Use exact service and entity names from the brand pack's coverage map. Do not
pluralise, abbreviate, or invent variants. If a name is not in the coverage
map, stop and ask rather than guessing.

## Compliance is not optional

Every brand pack has a `Compliance` section. Health and legal marketing carry
real regulatory constraints. Any draft containing a claim flagged there must be
marked `NEEDS REVIEW` at the top of the file with the specific claim quoted.
Never silently soften a claim to avoid the flag.

## Where brand packs come from

Notion is the source of truth. `brands/*.md` are fallback copies only — never
edit them by hand, and never treat them as current without checking the sync
timestamp in their header.

`/brief` fetches the pack live and writes `brand-pack-snapshot.md` into the
content folder. Every step after that reads the snapshot, not Notion. A piece is
produced against one fixed version of the rules from brief to publish, even if
someone edits the pack mid-production. `/qa` diffs the snapshot against live and
tells you if the rules moved.

## Working rules

- Every output is a file. Never return content only in chat.
- Never invent statistics, case outcomes, client names, or citations. If a claim
  needs a source, find one and link it, or cut the claim.
- Preserve the brief. If you disagree with the angle, say so before drafting,
  not by quietly writing something else.
- One content object fans out to many channels. Do not write a channel variant
  from scratch — derive it from the approved source piece.
