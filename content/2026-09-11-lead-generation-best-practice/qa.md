# QA: Lead-Generation Best Practice (Sanguine Legal Solutions)

Checked against `brand-pack-snapshot.md` in this folder. Files reviewed: `brief.md`, `source.md` (no channel variants exist yet — `/atomize` has not run on this piece).

## Update — 2026-09-11, post-first-pass
Per s.foley@sanguinesa.com in chat, three of the five original flags are resolved:
- **Footnotes [^2] and [^3] cut.** Both citations, and the specific claims they supported, were removed from `source.md` rather than left unsourced — footnote [^1] is the only citation remaining, and it was never in question. See the updated **Claims and citations** section below.
- **CTA confirmed current.** The `STATUS: NEEDS REVIEW` flag on the free lead-generation-review offer is resolved and removed from `source.md`.
- **Signatory named.** The live Notion pack was updated and re-fetched; `brand-pack-snapshot.md` was re-synced to match (see **Drift check**, below, for the full diff). Sue Foley is now named in the pack as Brand and marketing owner and is confirmed as the signatory for this piece.

The re-sync surfaced one thing worth flagging on its own: the pack's "Who signs off" list didn't just add Sue Foley, it also dropped the Legal/ethics review, Privacy/consent review, and Final publication authority rows that were previously "Unknown; confirm internally" — it no longer names anyone in those roles at all, rather than filling them in. Noted under **Compliance** below; not treated as blocking since the pack's own two remaining named roles are the ones actually being exercised here.

## Model integrity
No instance found where the copy implies Sanguine performs the underlying service (finding, generating, or delivering leads/cases) rather than vetting and connecting.

Checked specifically:
- "Sanguine Legal Solutions works with personal injury law firms on third-party lead generation through a four-part model" — connecting language, clean.
- "What Sanguine does is the vetting and testing work before a firm ever hears a pitch, the matching that follows, and the ongoing management once a source is live" — names only the advisory/vetting functions (vet, test, match, manage), not delivery. Clean.
- "The law firm and the provider then contract and work directly with each other. Sanguine isn't a party to that agreement, and no lead data passes through Sanguine to get there." — matches the required baseline disclosure, stated in the body per the snapshot's placement rule (not footer-only). Clean.

No failures on this axis.

## Naming
Checked every service/entity mention against the coverage map:
- "Sanguine Legal Solutions" — used correctly at full form on both appearances (¶ "Vet, test, deliver, manage" and ¶ "Where Sanguine fits"). "SLS" never appears in the draft. ✓
- "personal injury law firms" — spelled out correctly at first reference (¶ "Vet, test, deliver, manage," line 22). One other mention of "personal injury lead vendor" (line 10) is a generic search-query example, not a coverage-map term, so it doesn't need the exact form. ✓
- "Request a Lead-Generation Review" and "Book a Call" — both CTAs match the coverage map exactly, including case. ✓
- The four model-stage words (Vet / Test / Deliver / Manage) are preserved in word and order, each given its own bolded paragraph header. The pack's exact punctuated form "**Vet. Test. Deliver. Manage.**" doesn't appear as a single string anywhere — the draft always renders it as "vet, test, deliver, manage" in running prose or as four separate bolded labels. The pack's rule is "preserve the words and order," not the exact punctuation, so this is compliant, but flagging so a reviewer can decide if the exact stylized string should appear once for brand recognition.
- No banned variants found: no "Sanguine Law," "Sanguine Legal," "lead broker," "marketplace," "vendor directory," "provider certification," "guaranteed vendor," "Sanguine-approved leads."
- "doesn't sell leads, buy leads, hold lead inventory" (¶ "Where Sanguine fits") uses "buy leads" only inside a negation that mirrors the pack's own "What Sanguine Legal Solutions does not do" list. Not a violation — the banned list targets this phrase as promotional/CTA language ("Buy Leads" as a button), not as the object of a negation. Flagging only so it isn't misread on a fast pass.

No naming blockers.

## Claims and citations
**[^2] and [^3] cut, per direction.** Both the citations and the specific claims they supported (the "shared leads racing to call" line and the "resold, recycled, or re-aged... in writing" line) were removed from `source.md`, not just de-cited — consistent with "cut the claim" when a citation doesn't hold up. The surrounding paragraph was tightened so it reads cleanly with one example question instead of three.

One footnoted claim remains:

1. **[^1]** "is this vendor generating the lead itself, or reselling something bought from someone else and marked up" → Kurios, "How to Vet a Lead Vendor." Re-confirmed this session: Kurios's own summary of the article states it advises firms to confirm "whether it generates its own leads or resells them" as the first vetting question. Solid match. This citation was never in question and stayed as-is.

**Link resolution (carried-over flag):** I still could not directly fetch this URL — outbound requests to `kuriosbrand.com` were blocked by this sandbox's network egress policy (not a dead-link signal, a sandbox restriction). The URL and its exact page title were independently re-confirmed live in search results this session, which is reasonable evidence it currently exists, but nobody has confirmed the page returns 200 and still contains the cited passage. **Flag: verify this one remaining link resolves before this ships.**

No uncited factual claims found elsewhere in the piece — everything else is either Sanguine's own approved-proof language or a description of the reader's situation, neither of which requires external sourcing.

## Proof
Every proof point used traces to the snapshot's "Approved strategic proof" list: no-leads-pass-through-Sanguine, firm-first assessment, provider vetting (described as vetting, not certification), sources tested before broader delivery, ongoing management, direct commercial relationship, and the free lead-generation review offer. No figure, count, rate, named client, named provider, or testimonial appears anywhere in the draft — confirmed clean against the "Proof that is not yet approved" list (all still Unknown, none used).

## Compliance
- **CTA currency confirmed.** The "free, no-obligation" lead-generation review offer is confirmed current; the `STATUS: NEEDS REVIEW` marker has been removed from `source.md`. The pack itself was also updated to drop its own "confirm free remains current before each campaign" caveat on this line (see Drift check).
- Every other compliance flag from `brief.md` held: descriptive-only language for vetting/testing (no "certifies," "guarantees," "approves as compliant" found), no implied guarantee tied to the "test" stage, no named or ranked provider, no compensation/commission framing, and the required baseline disclosure appears in the body rather than only a footer.
- **Signatory named, routing resolved.** The pack now names Sue Foley, CMO & President, Sanguine Marketing Solutions, as Brand and marketing owner, confirmed in chat as the approver for this piece. That closes the original routing gap for this content.
- **Worth flagging on its own:** the pack update didn't just add Sue Foley — it replaced a six-role sign-off list (which had three roles marked Unknown) with a two-role list, and the three dropped roles were **Legal and ethics review**, **Privacy and consent review**, and **Final publication authority**. Those weren't filled in, they were removed. For this specific piece that's not a blocker — Sue Foley's sign-off as Brand and marketing owner is the approval this content needs, and Anthony Bux remains named as Business owner — but the pack no longer names anyone responsible for legal/ethics or privacy review on SLS content generally. Worth a quick internal check that this was the intended change and not just consolidation for speed.

## Voice
- The single idea holds to the two-sentence rule (brief's own "single idea" statement is two sentences; the draft's opening paragraph mirrors it in two sentences).
- No stock phrases from the house list ("unlock," "leverage," "game-changing," "in today's landscape," "it's worth noting") appear.
- No rhetorical questions used as section openers. The one bulleted list of questions (¶ "What a questionnaire can't see yet") is functional content — things to ask — not a rhetorical device.
- Em-dash asides and "not X but Y" constructions were checked and edited out during drafting; none remain in the current file.
- Nothing reads as templated/swappable-with-a-competitor-name: the piece's central move (vet vs. test vs. manage, citing the actual competing checklists by content rather than name) is specific to this brand's approved operating model and wouldn't survive a straight brand-name swap.

No hedged or templated language flagged.

## Links and UTMs
- One external citation link remains, a plain URL (no UTM parameters), which is appropriate for an outbound citation to a third-party source.
- No internal Sanguine links or CTAs carry a URL yet — `source.md` is prose referencing CTA labels ("Request a Lead-Generation Review," "Book a Call"), not live hyperlinks, so there is nothing to build or check a UTM against at this stage. This should be revisited once the piece is placed on an actual landing page or in an atomized channel variant with real links.
- See **Claims and citations** above for the link-resolution flag on the remaining footnote.

## Derivation
No channel variants exist in this folder yet (`/atomize` hasn't been run). Nothing to check here — noting it so this isn't mistaken for an oversight.

## Drift check
**First pass (initial QA):** fetched the live Notion page and compared against the snapshot. No drift — the live page's `page_last_edited_at` (2026-09-11T03:12:12.015Z) predated the snapshot's fetch timestamp (2026-09-11T03:12:53.179Z), and the full content matched word-for-word.

**Second pass (this update):** re-fetched the live page after being told the pack had changed. It had — `page_last_edited_at` moved to 2026-09-11T04:42:31.842Z. Two changes, confirmed by close comparison against the snapshot (line-by-line diff on the retyped coverage-map and sign-off sections; the rest of the pack was read through in full and found unchanged):

1. **Coverage map, "lead-generation review" row:** the notes column dropped "third-party" from the service description and dropped the sentence "Confirm that **free** remains current before each campaign" entirely. The offer is now stated as simply current.
2. **"Who signs off"** was rewritten from six roles (Business owner, Brand and marketing owner, Legal and ethics review, Privacy and consent review, Provider claims, Final publication authority — three of them Unknown) down to two: Business owner (Anthony Bux, VP, Sanguine Legal Solutions) and Brand and marketing owner (Sue Foley, CMO & President, Sanguine Marketing Solutions).

`brand-pack-snapshot.md` has been updated in place to match, with a note at the top of the file recording what changed and when, per the house rule that a piece is produced against one fixed version of the rules and any mid-production pack edit gets surfaced rather than silently absorbed. Nothing else in the pack moved — the coverage map, proof lists, voice rules, compliance sections (other than sign-off), channels, and pillars are all unchanged from the version this piece was briefed and drafted against.

## Summary of flags

**Resolved this update:**
1. ~~Tighten or soften the [^3] citation~~ — cut, along with the claim it supported.
2. ~~Spot-check [^2]~~ — cut, along with the claim it supported.
3. ~~Confirm the free lead-generation-review offer is still current~~ — confirmed; `STATUS: NEEDS REVIEW` removed from `source.md`; the pack's own caveat on this line was also dropped.
4. ~~No named signatory for sign-off~~ — resolved; Sue Foley, CMO & President, Sanguine Marketing Solutions, confirmed as the approver for this piece via the pack's "Brand and marketing owner" role.

**Still open:**
1. Verify the one remaining footnoted link (Kurios) resolves and still contains the cited claim — sandbox network policy blocked direct verification this session; only re-confirmed via search index.
2. Worth an internal check (not blocking this piece): the pack's sign-off list no longer names anyone for legal/ethics review, privacy/consent review, or final publication authority — those roles were removed rather than filled in when Sue Foley was added. Confirm that was intentional.

Nothing in the copy itself was ever a defect — the draft stayed inside every guardrail the snapshot set from the first pass. What's left is one live-link check and one internal question about the pack's own sign-off coverage going forward.

**PASS WITH FLAGS**
