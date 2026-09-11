# QA: Lead-Generation Best Practice (Sanguine Legal Solutions)

Checked against `brand-pack-snapshot.md` in this folder. Files reviewed: `brief.md`, `source.md` (no channel variants exist yet — `/atomize` has not run on this piece).

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
Three footnoted claims, all sourced to real, specific pages found via live web search this session:

1. **[^1]** "is this vendor generating the lead itself, or reselling something bought from someone else and marked up" → Kurios, "How to Vet a Lead Vendor." Re-confirmed this session: Kurios's own summary of the article states it advises firms to confirm "whether it generates its own leads or resells them" as the first vetting question. Solid match.
2. **[^2]** "Has it been resold, recycled, or re-aged, and will the vendor put that answer in writing" → Exclusive Leads Agency, "How to Vet an MVA Lead Provider: 12 Questions to Ask." This matches the original search summary of that page. A re-query this session surfaced other content from the same URL (pricing, DNC/consent compliance) without re-surfacing the exact resold/recycled/re-aged line, so I could not re-confirm this specific sentence word-for-word this pass — flagging for a human to spot-check that exact claim against the live page before publish.
3. **[^3]** "shared with several others racing to call the same person first" → attributed to Mohr Marketing's "Exclusive Personal Injury Leads" guide. Re-confirmed this session that the page defines exclusive leads as "a strict one-to-one ratio... eliminates the friction of immediate competition," which supports the underlying claim, but the specific phrase "racing to call" traces back to a different, unattributed source in my original research pass (a multi-source search summary), not confirmed as mohrmktg.com's own wording. **Flag: tighten this citation or soften the phrasing before publish** — the concept is supported, the exact framing may not be this source's own language.

**Link resolution:** I could not directly fetch any of the three URLs this session — outbound requests to `kuriosbrand.com`, `exclusiveleadsagency.com`, and `mohrmktg.com` were blocked by this sandbox's network egress policy (not a dead-link signal, a sandbox restriction). All three URLs and their exact page titles were independently re-confirmed live in search results this session, which is reasonable evidence they currently exist, but nobody has confirmed the pages return 200 and still contain the cited passages. **Flag: verify all three links resolve and still contain the quoted claims before this ships**, since neither this session nor the original draft pass could do that directly.

No uncited factual claims found elsewhere in the piece — everything else is either Sanguine's own approved-proof language or a description of the reader's situation, neither of which requires external sourcing.

## Proof
Every proof point used traces to the snapshot's "Approved strategic proof" list: no-leads-pass-through-Sanguine, firm-first assessment, provider vetting (described as vetting, not certification), sources tested before broader delivery, ongoing management, direct commercial relationship, and the free lead-generation review offer. No figure, count, rate, named client, named provider, or testimonial appears anywhere in the draft — confirmed clean against the "Proof that is not yet approved" list (all still Unknown, none used).

## Compliance
- The one claim the brief flagged as needing a currency check — the "free, no-obligation" lead-generation review offer — is correctly marked `STATUS: NEEDS REVIEW` on line one of `source.md`, with the claim quoted beneath it, per house rule.
- Every other compliance flag from `brief.md` held: descriptive-only language for vetting/testing (no "certifies," "guarantees," "approves as compliant" found), no implied guarantee tied to the "test" stage, no named or ranked provider, no compensation/commission framing, and the required baseline disclosure appears in the body rather than only a footer.
- **Routing gap (flag, not a draft defect):** the snapshot names no one who can actually sign off on this content. "Legal and ethics review," "Privacy and consent review," and "Final publication authority" are all listed as **Unknown; confirm internally** in the pack, and the one named role that does exist — Anthony Bux as business owner — carries its own "confirm title and authority before use" caveat (moot here since he isn't named in this draft). Since this piece falls squarely inside "any description of provider vetting, testing, due diligence or acceptance criteria" — the pack's own top compliance-review category — it cannot be routed to a named signatory as things stand. This needs to be resolved internally (naming the actual legal/ethics reviewer and final approver) before this piece, or any SLS content, can clear a real sign-off step.

## Voice
- The single idea holds to the two-sentence rule (brief's own "single idea" statement is two sentences; the draft's opening paragraph mirrors it in two sentences).
- No stock phrases from the house list ("unlock," "leverage," "game-changing," "in today's landscape," "it's worth noting") appear.
- No rhetorical questions used as section openers. The one bulleted list of questions (¶ "What a questionnaire can't see yet") is functional content — things to ask — not a rhetorical device.
- Em-dash asides and "not X but Y" constructions were checked and edited out during drafting; none remain in the current file.
- Nothing reads as templated/swappable-with-a-competitor-name: the piece's central move (vet vs. test vs. manage, citing the actual competing checklists by content rather than name) is specific to this brand's approved operating model and wouldn't survive a straight brand-name swap.

No hedged or templated language flagged.

## Links and UTMs
- Three external citation links present, all plain URLs (no UTM parameters), which is appropriate for outbound citations to third-party sources.
- No internal Sanguine links or CTAs carry a URL yet — `source.md` is prose referencing CTA labels ("Request a Lead-Generation Review," "Book a Call"), not live hyperlinks, so there is nothing to build or check a UTM against at this stage. This should be revisited once the piece is placed on an actual landing page or in an atomized channel variant with real links.
- See **Claims and citations** above for the link-resolution flag on the three footnotes.

## Derivation
No channel variants exist in this folder yet (`/atomize` hasn't been run). Nothing to check here — noting it so this isn't mistaken for an oversight.

## Drift check
Fetched the live Notion page (`https://app.notion.com/p/c65ec04601ef83d6846b01021359d17b`) and compared against `brand-pack-snapshot.md`. **No drift.** The live page's `page_last_edited_at` (2026-09-11T03:12:12.015Z) predates the snapshot's fetch timestamp (2026-09-11T03:12:53.179Z) — the snapshot was taken after the last edit and the full content matches word-for-word. The pack has not moved since the brief was approved; this piece is still being produced against current rules.

## Summary of flags
1. Verify the three footnoted external links resolve and still contain the cited claims (sandbox network policy blocked direct verification this session).
2. Tighten or soften the [^3] citation — the "racing to call" framing isn't confirmed as Mohr Marketing's own wording.
3. Spot-check [^2]'s exact "resold, recycled, or re-aged... in writing" claim against the live page before publish.
4. Confirm the free lead-generation-review offer is still current (already marked `STATUS: NEEDS REVIEW` in `source.md`).
5. No named signatory exists in the pack for legal/ethics review or final publication authority — this needs to be resolved internally before any SLS content, including this piece, can get a real compliance sign-off.

None of these are defects in what was drafted — the copy stays inside every guardrail the snapshot sets. They're gaps in verification and in the pack's own sign-off chain that a human needs to close before this goes live.

**PASS WITH FLAGS**
