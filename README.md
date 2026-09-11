# Sanguine Content Engine

A content pipeline anyone on the team can run. Four commands, two human gates,
one source of truth per brand.

## Before first use

Fill in the brand packs in `brands/`. This is the whole game. The commands are
thin; the brand packs are what stop the output being generic. Budget a proper
session per brand — the coverage map and compliance sections especially.

A half-filled brand pack produces confident, wrong content.

## The loop

```
/brief <brand> "<topic>"     →  content/<date>-<slug>/brief.md
      ↓  HUMAN GATE — approve the angle
/draft <folder>              →  source.md
      ↓
/atomize <folder>            →  distribution/ (one file per channel)
      ↓
/qa <folder>                 →  qa.md
      ↓  HUMAN GATE — read the actual copy
   publish
```

## Why it scales

The unit of production is not a blog post. It is a **content object** that fans
out. One approved source piece becomes a blog, three LinkedIn posts, a
newsletter section, a 1:1 sales email, static social, and paid variants.

Going from four brands to eight brands should not mean eight times the work. It
means eight brand packs and the same four commands.

## The two gates, and why they stay

**Brief approval** is where judgment lives. Wrong angle, wrong pillar, wrong
reader — everything downstream inherits it, and re-running is cheap only if you
catch it here.

**Pre-publish** is where a human reads the actual words. `/qa` catches
mechanical failures. It does not catch "this is technically fine and still
embarrassing."

Everything between those two gates can run unattended.

## Running it for the team

The commands take fixed arguments so they are not prompts anyone has to hold in
their head. Someone who has never used Claude Code should be able to run
`/brief biz-head-law "co-counsel fee splits"` and get something useful.

When output is consistently wrong in the same way, fix the brand pack or
`CLAUDE.md` — not the individual draft. The drafts are disposable. The context
files compound.

## Structure

```
CLAUDE.md                 global rules — read on every run
brands/                   one pack per brand; the real IP
.claude/commands/         the four pipeline steps
content/<date>-<slug>/    one folder per content object
pillars/                  recurring themes per brand
```
