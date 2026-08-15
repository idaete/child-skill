# /child — The CHILD Framework as an Agent Skill

A thinking companion built from *A Child in Us: The Creative Thinking Handbook* by Gaurav Yadav.

Bring it a real problem — a decision you're circling, a project that's stuck, a pitch you can't
simplify — and it thinks through it with you using the five CHILD traits, as a loop rather than a
checklist:

**C**uriosity → **H**euristics → **I**magination → **L**aconic → **D**eductive → back to Curiosity.

Each move feeds the next. Curiosity sharpens the question. Heuristics narrows it. Imagination
pushes past the constraint. Laconic compresses the result. Deductive tests whether it holds — and
that test surfaces the next question.

---

## Install

### Claude (web, desktop, or mobile)

You'll need a Claude account on **Pro, Max, Team, or Enterprise**, with **Code execution and file
creation** enabled in Settings → Capabilities.

1. Download this repo as a ZIP (**Code → Download ZIP**), or clone it.
2. Zip the `child/` folder on its own. The ZIP's root must contain `child/`, and inside it
   `SKILL.md` and `references/` — not the files loose, and not wrapped in an extra folder.
3. In Claude, go to **Customize → Skills**.
4. Click **+** → **Create skill** → upload the ZIP.
5. Toggle the skill on.

### Claude Code

No ZIP needed — copy the `child/` folder into either:

- `~/.claude/skills/` — available in every project
- `.claude/skills/` — available in one project only

### Other tools

`/child` follows the open [Agent Skills](https://agentskills.io) specification, so it works in any
compatible tool — Cursor, GitHub Copilot, Gemini CLI, VS Code and others. Drop the `child/` folder
into that tool's skills directory; check its docs for the exact path.

---

## Try it

Once installed, start a new chat and bring it something real:

> I've got two directions for my next project and I keep flip-flopping. /child this.

> Our onboarding drops 60% of users at step three and I don't know why. /child

You don't have to type `/child` — describing a genuine problem is usually enough to trigger it.

---

## What's inside

```
child/
├── SKILL.md                           # The framework and the thinking protocol
└── references/
    ├── child-pillars-deep.md          # Full doctrine per trait, with exercises
    ├── child-examples-casestudies.md  # Book characters and real applications
    └── gaurav-book-voice.md           # Tone guide for writing CHILD material
```

Only `SKILL.md` loads by default. The reference files are read on demand — when a session goes deep
on one trait, needs an illustration, or writes in the book's voice.

---

## About the framework

CHILD holds that the traits children use instinctively — curiosity, resourcefulness, imagination,
clarity, and logic — aren't lost in adulthood, only buried under responsibility, expectation, and
the fear of looking incompetent. The framework is excavation, not construction.

Unlike personality instruments that sort people into fixed types, CHILD treats all five traits as
trainable capacities that vary in strength within the same person and change with practice.

- **Read the book:** [achildinus.com](https://achildinus.com)
- **Take CHILDex**, the free creative thinking assessment: [achildinus.com/childex](https://achildinus.com/childex)

---

## Notes

This is an independent skill built by the book's author. It isn't affiliated with or endorsed by
Anthropic, and "Claude" is a trademark of Anthropic.

## Copyright & License

*A Child in Us: The Creative Thinking Handbook* © Gaurav Yadav. 
All rights reserved. The book, the CHILD Framework, and all content 
derived from them remain the intellectual property of the author.

The skill files in this repository are made available under 
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) — 
share and adapt with attribution, non-commercially, under the same terms.

This license applies to the contents of `child/` as distributed here. 
It does not grant any rights to the book itself, in whole or in part.

## Feedback

Open an issue in this repo, or get in touch via [achildinus.com](https://achildinus.com).
