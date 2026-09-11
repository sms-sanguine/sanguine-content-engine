# UTM tracking — Lead-Generation Best Practice (Sanguine Legal Solutions)

**Flag: no UTM convention exists in `CLAUDE.md` yet.** The `/atomize` instructions point there for "the convention," but the file doesn't define one. Rather than stop, I've set a plain, standard convention below and applied it consistently across every variant in this folder. Treat this as a proposal to formalize in `CLAUDE.md` — once a house convention exists, re-derive these to match it exactly.

## Convention used here

`utm_source` = the platform or send channel · `utm_medium` = the traffic type · `utm_campaign` = fixed for this content piece, every channel · `utm_content` = distinguishes one variant/asset from another in the same channel · `utm_term` = paid search only, the matched keyword theme.

`utm_campaign` for this piece: **`2026-09-lead-vetting-guide`**

## Destination pages (placeholders — replace before send)

None of these three pages exist yet at a confirmed live URL. The bracketed slugs below are placeholders standing in for wherever these actually get published. **Do not send or traffic anything against these exact URLs — swap in the real, live paths first.**

| Label | Placeholder URL | Used for |
|---|---|---|
| **Article** | `https://sanguinesa.com/legal-solutions/resources/[GUIDE-SLUG]` | The source piece itself, once it has a live page |
| **Request a Lead-Generation Review** | `https://sanguinesa.com/legal-solutions/lead-generation-review` | The approved CTA/offer page |
| **Book a Call** | `https://sanguinesa.com/legal-solutions/book-a-call` | The approved low-pressure CTA/booking page |

## Full link table

Every link that appears in any distribution file, in one place, so nothing drifts if a UTM needs to change later.

| File | Variant | Destination | Full URL with UTMs |
|---|---|---|---|
| `linkedin-organic.md` | Post 1 — "The checklist isn't wrong" | Article | `[ARTICLE]?utm_source=linkedin&utm_medium=organic-social&utm_campaign=2026-09-lead-vetting-guide&utm_content=post-1-checklist-limit` |
| `linkedin-organic.md` | Post 2 — "A vendor comfortable being vetted" | Article | `[ARTICLE]?utm_source=linkedin&utm_medium=organic-social&utm_campaign=2026-09-lead-vetting-guide&utm_content=post-2-comfortable-answer` |
| `linkedin-organic.md` | Post 3 — "Ask what happens after signing" | Article | `[ARTICLE]?utm_source=linkedin&utm_medium=organic-social&utm_campaign=2026-09-lead-vetting-guide&utm_content=post-3-after-signing` |
| `newsletter.md` | Section CTA | Article | `[ARTICLE]?utm_source=newsletter&utm_medium=email&utm_campaign=2026-09-lead-vetting-guide&utm_content=newsletter-section` |
| `sales-email.md` | Primary CTA | Request a Lead-Generation Review | `[REVIEW]?utm_source=sales-email&utm_medium=email&utm_campaign=2026-09-lead-vetting-guide&utm_content=rep-1to1-primary` |
| `sales-email.md` | Secondary link (optional, if rep wants to send the article instead) | Article | `[ARTICLE]?utm_source=sales-email&utm_medium=email&utm_campaign=2026-09-lead-vetting-guide&utm_content=rep-1to1-article` |
| `social-static.md` | Asset 1 — "Vet, Test, Deliver, Manage" | Article | `[ARTICLE]?utm_source=linkedin&utm_medium=organic-social&utm_campaign=2026-09-lead-vetting-guide&utm_content=static-1-model` |
| `social-static.md` | Asset 2 — "An answer is not evidence" | Article | `[ARTICLE]?utm_source=linkedin&utm_medium=organic-social&utm_campaign=2026-09-lead-vetting-guide&utm_content=static-2-quote` |
| `social-static.md` | Asset 3 — "What a questionnaire can't see yet" | Article | `[ARTICLE]?utm_source=linkedin&utm_medium=organic-social&utm_campaign=2026-09-lead-vetting-guide&utm_content=static-3-question` |
| `paid-variants.md` | Pair 1–5 | Request a Lead-Generation Review | `[REVIEW]?utm_source=google&utm_medium=cpc&utm_campaign=2026-09-lead-vetting-guide&utm_content=paid-{1..5}&utm_term=vet+lead+provider` |

`[ARTICLE]`, `[REVIEW]`, and `[BOOK]` above stand for the placeholder destination URLs in the table further up — spelled out in full in each individual distribution file so a rep or ad platform can copy-paste directly, once the real destination URLs are swapped in.

## Open flag carried from `paid-variants.md`
The approved brief for this piece explicitly says: *"Do not push this through paid search/display as a standalone asset yet — it's an educational piece meant to earn organic and AEO visibility and support the referral/relationship channels first."* `paid-variants.md` was still produced, per `/atomize`'s default fan-out, but is marked **not authorized for spend** at the top of that file. Its UTMs are included here so they're ready and consistent whenever that changes, not as a signal that they're cleared to use now.
