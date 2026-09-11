# Copywriter's Handbook — Claude Skill

A Claude skill that turns Claude into a direct-response copywriter, grounded in the principles of Robert W. Bly's *The Copywriter's Handbook* (4th edition).

Not "make it sound nice" copywriting. Copy that sells — researched, structured, and checked against proven frameworks before it reaches you.

## What it does

When installed, Claude automatically applies this skill to any copywriting request — landing pages, emails, subject lines, ads, social posts, video scripts, sales letters, product descriptions, and more.

Instead of drafting from vibes, Claude:

1. **Researches first** — mines your files and conversation, then web-researches your product, competitors, and audience language before writing a word
2. **Builds a BDF profile** — maps your audience's Beliefs, Desires, and Feelings to pick the right emotional angle
3. **Translates features into benefits** — with the "so what?" test applied to every feature
4. **Selects the right copy formula** — AIDA, ACCA, 4 P's, or Bly's Motivating Sequence, chosen based on product and audience, not at random
5. **Scores headlines with the 4 U's** — Urgent, Unique, Ultra-specific, Useful — and gives you 3–5 alternatives
6. **Runs a 10-point quality checklist** before handing over the draft

## What's inside

```
copywriters-handbook/
├── SKILL.md              # Core methodology: research process, headline rules,
│                         # clarity formulas, persuasion structure, quality checklist
└── references/           # 32 format-specific playbooks + swipe files
    ├── research-process.md, copy-formulas.md, proof-techniques.md,
    │   positioning.md, generational-marketing.md ...
    ├── Format guides: landing pages, email, social, online ads, video,
    │   content marketing, print, direct mail, brochures, PR, TV/radio, websites
    └── Swipe files: proven headline patterns and real examples per format
```

Claude reads the relevant reference + swipe file for your format before writing, so a landing page draws on landing-page principles, not generic advice.

## Install

**Claude.ai (web/app):**
1. Download this repo (green **Code** button → **Download ZIP**) and unzip
2. Go to **Settings → Capabilities → Skills** → upload the `copywriters-handbook` folder
3. Start a new chat and ask for any copy — the skill triggers automatically

**Claude Code:**
1. Copy the `copywriters-handbook` folder into your skills directory (`~/.claude/skills/`)
2. Restart Claude Code

## Usage

No special commands. Just ask:

- "write a landing page for my skincare brand"
- "draft a 5-email welcome sequence"
- "give me 10 headline options for this offer"
- "make this ad copy more persuasive" (paste the copy)

Tip: the more product info, proof, and audience detail you give upfront, the less Claude needs to ask — but it will ask for what's genuinely missing rather than guessing.

## Credits

Methodology distilled from *The Copywriter's Handbook* (4th edition) by Robert W. Bly. This skill is an educational summary of its principles — buy the book, it's worth it.

## License

MIT — use it, fork it, adapt it for your own stack.
