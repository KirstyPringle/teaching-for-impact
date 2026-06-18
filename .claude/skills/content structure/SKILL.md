This guide covers content structure. For voice, register, and tone, see the voice and tone skill.

# Content Style Guide: Advocacy for Institutional Environmental Sustainability

This guide explains how content is structured in this course and how to write for each layer. Use it as a reference when creating or editing any part of the materials.

---

## Two Layers, One Document

Every content file serves two purposes at once. The same markdown source produces:

1. **Slides** — for use in live workshops and facilitated sessions
2. **Background reading / website** — for self-directed learners, or for participants who want more depth after a session

These two layers live in the same file. What separates them is whether content sits **inside** or **outside** the block comment tags.

---

## The Block Tags

Content blocks are wrapped in HTML comment tags that identify their type:

```
<!-- type: concept -->

Content here appears on slides.

<!-- end: type -->
```

Everything **inside** these tags goes on the slides. Everything **outside** them is background prose for the website or self-study version.

### Block types in use

| Tag | Purpose |
|---|---|
| `<!-- type: concept -->` | Core teaching content — definitions, frameworks, key ideas |
| `<!-- type: framework -->` | A named model or structured approach (e.g. Diffusion of Innovations) |
| `<!-- type: exercise -->` | An activity or discussion prompt for participants |
| `<!-- type: reflection -->` | A pause point — something to sit with rather than answer immediately |
| `<!-- type: quote -->` | A pull quote, usually in an `!!! quote` admonition |
| `<!-- type: example -->` | A worked example or case study (e.g. Greendale University) |

---

## Writing for Slides (Inside the Tags)

Slides are what a facilitator presents in a room. Participants are listening, not reading — so slide content needs to anchor the spoken explanation, not replace it.

**Use short bullets.** Each bullet is a phrase or short clause, not a full sentence. Write the key term or the core idea; the facilitator provides the context.

**Bold the signal word.** When a bullet introduces a named concept or category, bold the term and follow it with a dash and a brief descriptor.

**Keep it scannable.** A slide block should be readable in a few seconds. If it takes longer than that, it is probably trying to do too much. Split it, or move the detail outside.

**Headings are optional but useful.** Use a `##` heading to title a slide block when the heading will display on screen. Some blocks follow on logically from a preceding heading and do not need one.

**Use `<!-- slide break -->` for longer blocks.** If a concept needs two slides, insert `<!-- slide break -->` where the split should happen. Do not use this to cram more content onto a slide — use it when a natural break genuinely exists.

### Example

```markdown
<!-- type: concept -->

## Choosing Where to Start

Choose a starting point that gives you the best chance of early success:

- **Start small** — builds credibility, skills, and community with less risk
- **Pick something already widely supported** — look mainstream, not radical
- **Pick something immediately useful** — changes that help people stick
- **Use existing relationships** — *"we think"* is more persuasive than *"I think"*

<!-- end: type -->
```

---

## Writing for Background / Website (Outside the Tags)

The prose outside the block tags is the full version — the explanation behind the slide, the context that makes the idea land, the reasoning that the bullets compress away.

**Write in flowing paragraphs.** This is not a transcript of a lecture. It is reading material, written to be read. Use full sentences and let ideas connect across them.

**Expand on what the slide compressed.** A slide bullet might say *"Use existing relationships."* The background prose explains why: that movements are built on pre-existing trust, that *"we think"* is more persuasive than *"I think"*, and that arriving with colleagues changes the dynamic of the conversation entirely. The bullet cues the idea; the prose earns it.

**Use bullets sparingly.** Only use bullet lists in background prose when items are genuinely enumerable and parallel — a list of funder requirements, for example, or a checklist of specific actions. Do not use bullets as a substitute for prose when ideas connect. If you are tempted to write three bullets where the second explains the first, write a paragraph instead.

**Do not repeat the slide.** The background prose is not a restated version of what the slide said. It adds depth, example, or nuance. A reader who already understood the slide should still get something from reading the background.

**Maintain the voice.** See the voice and tone guide. Direct, warm, practical. No hedging, no filler, no motivational padding.

### Example

Following the slide example above, the background prose might read:

```markdown
The best starting point is rarely the most ambitious one — and that is not a compromise, it is strategy.

Start with something small. A small win builds your credibility, develops your skills, and creates a group of people who have done something together — which is itself a foundation for what comes next. It also limits the damage if things do not work out.

Pick something already widely supported. You want to appear to be part of a mainstream direction of travel, not a lone voice pushing against the current. Look for changes that align with what the institution already says it wants to do, or with things colleagues regularly raise but nobody has fixed.
```

---

## Callout Boxes

Callout boxes (admonitions) appear both inside and outside block tags, depending on their purpose.

| Syntax | Use |
|---|---|
| `!!! tip` | A practical pointer — something actionable the reader can use immediately |
| `!!! quote` | A direct quotation, usually from a named source |
| `!!! question "Activity – [title]"` | An activity or reflection prompt for participants |
| `!!! Learning Outcomes` | Listed at the top of each section, outside block tags |
| `!!! Example "[title]"` | A named example or case study |

Activities (`!!! question`) almost always sit inside an `<!-- type: exercise -->` block. Tips and quotes can sit inside or outside block tags depending on whether they belong on the slide or in the background only.

---

## Learning Outcomes

Each section opens with a `!!! Learning Outcomes` block, outside the slide tags. These are written as "be able to..." or "understand..." statements, not as topic headings.

```markdown
!!! Learning Outcomes

    - Know how to find a realistic and effective starting point for your advocacy
    - Understand how change spreads, and what that means for who you involve first
    - Be able to build a coalition and navigate institutional decision-making
```

---

## Section Headings

Top-level sections use `#` headings and are usually wrapped in a short `<!-- type: concept -->` block containing only the heading. This puts the section title on a slide on its own.

```markdown
<!-- type: concept -->

# Section 4 – Implement Your Plan

<!-- end: type -->
```

Subsections within a slide block use `##`. Background prose uses `###` subheadings if navigation within a long passage would help the reader — but use these sparingly.

---

## What Each Layer Is Not

**Slides are not self-contained.** They are designed to be spoken to. A participant who only has the slides should be able to follow the structure, but they will not have the full picture. That is intentional.

**Background prose is not a transcript.** It is not a written-out version of what a facilitator might say. It is independent reading material that works on its own, for someone who was not in the room.

**The two layers should complement, not duplicate, each other.** If the slide says it and the background says it again in nearly the same words, something is wrong. The background should add value that the slide cannot — depth, example, reasoning, nuance.
