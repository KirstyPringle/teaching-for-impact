# Part 1 Lesson Refactoring Plan

## Why this refactoring is needed

Part 1 currently has 8 lessons. After reading all of them, several structural issues stand out:

- Some lessons cover too much ground and try to do too many things at once
- Some lessons repeat concepts that were already covered elsewhere
- Some lesson boundaries are unclear, making it hard for readers to know where one topic ends and the next begins

The goal of this refactoring is to give each lesson a clear, focused purpose — without losing any of the 41 learning outcomes or 10 activities currently in Part 1.

---

## Gap analysis

A critical review of Part 1 against the primary audience (researchers, academics, and practitioners who are **not trained in pedagogy**, many encountering instructional design for the first time, working in **resource-constrained environments**) surfaced two gaps:

### Gap 1: Facilitation and delivery

The workbook teaches people to **design** training but never teaches them to **deliver** it. These are first-time trainers. A beautifully designed training can fail completely with poor facilitation.

The gap is visible in the existing content: Lesson 6 tells readers to "write it so that another facilitator could run the activity" but nowhere does the workbook teach what facilitation looks like in practice. Lesson 7 mentions "facilitator feedback" without teaching what good facilitation feedback involves. The role table in Lesson 1 distinguishes instructor/facilitator/co-designer but never teaches the skills any of those roles require.

First-time trainers need guidance on: running a session (opening, closing, transitions), time management, group dynamics, reading the room, working with co-facilitators or interpreters, and what to do when things go wrong.

**Decision:** Facilitation and delivery is important but is not part of the core design workflow. It belongs in a new **Extra Topics** section alongside other supplementary material.

### Gap 2: Evaluation for impact sits awkwardly in Part 1

The proposed Lesson 10 (Evaluation for Impact) covers understanding change over time, collecting evidence beyond the training event, and signal vs noise. While valuable, this is not core to the design workflow — it looks forward to what happens after delivery, not at the design itself. Assessment for learning (proposed Lesson 9) is tightly coupled to outcomes and activities; evaluation for impact is a broader, longer-term concern.

**Decision:** Move Evaluation for Impact to the **Extra Topics** section. Part 1 ends at Lesson 9 (Assessment for Learning), which completes the design arc. The bridge to Part 2 moves to the Part 1 closing or index page.

---

## Problems in detail

### Problem 1: Lessons 5 and 6 overlap on co-design and participation

Lesson 5 ("Co-Design and Constraints") introduces the distinction between co-design and co-creation, explains meaningful participation, and covers constraints. Lesson 6 ("Designing Learning Experiences for Participation and Co-Creation") then re-introduces co-creation as it applies within activities, re-covers participation design, and re-covers adapting to context.

The intended distinction — co-design shapes the training itself, co-creation happens within activities — is too subtle. A reader finishing Lesson 5 and starting Lesson 6 will feel like they're reading the same ideas again. The co-design vs co-creation distinction in Lesson 5 (lines 69-101) takes up a significant amount of space explaining a difference that only becomes meaningful in Lesson 6.

### Problem 2: Lesson 6 repeats Lesson 3 concepts

Lesson 3 ("How People Learn") introduces cognitive load, retrieval, active learning, and social learning as its core concepts. Lesson 6 then re-introduces cognitive load management and retrieval (lines 73-78) as part of its guidance on activity design. These are presented as if they are new ideas, which makes Lesson 6 feel bloated and makes Lesson 3 feel like it didn't land.

### Problem 3: Lessons 6 and 7 have a fuzzy boundary

Both Lesson 6 and Lesson 7 reference Activity 9 (Practice & Feedback Plan) — Lesson 6 as a "revisit" (line 153), Lesson 7 as its primary home (line 122). Lesson 6 covers scaffolding and sequencing; Lesson 7 covers practice and iteration. These are closely related, and the line between "designing activities" and "designing practice within activities" is not clear to the reader.

### Problem 4: Lesson 1 covers too much ground

Lesson 1 ("Training as a System Intervention") is the longest lesson at approximately 2400 words. Other lessons range from 800-1800 words. It covers four distinct conceptual areas: system mapping, Theory of Change, positionality/power, and role selection. Each of these is substantial enough to need its own space. The lesson also includes a full worked example that, while useful, adds to the density.

---

## Proposed new structure

The proposal is to go from 8 lessons to 9, with a new Extra Topics section. The split of Lesson 1 adds one lesson; the tightening of Lessons 5-7 removes overlap without merging lessons; Lesson 8 is narrowed to assessment only, with evaluation moving to Extra Topics.

### New Lesson 1: Training as a System Intervention

**Source:** First half of current Lesson 1 (through end of "Mapping your system" section, plus the worked example)

**Covers:**
- Why training is systemic — it happens inside organisations, communities, funding structures
- System mapping — identifying actors, resources, constraints, relationships
- Clusters (fragile concentration points), gatekeepers, missing connections
- The worked example (climate data training) — demonstrates system mapping in action

**Activities:** Activity 1 (System Map)

**Why this works as a standalone lesson:** System mapping is a substantial thinking tool. It asks the reader to draw a diagram, identify actors, find fragile points. That is enough cognitive work for one lesson. Combining it with Theory of Change means the reader has to hold two big frameworks in their head at once before practising either.

### New Lesson 2: Theory of Change, Positionality, and Your Role

**Source:** Second half of current Lesson 1 (from "From system to theory of change" through end)

**Covers:**
- Theory of Change chain: inputs → activities → outputs → outcomes → impact
- Building a ToC step by step — starting from impact and working backwards
- Surfacing assumptions and risks (what has to be true for each link in the chain)
- Positionality and power — training is not neutral, your choices reflect your position
- Role selection — instructor, facilitator, co-designer, and when each fits

**Activities:** Activity 2 (Theory of Change)

**Why these three belong together:** Your Theory of Change is shaped by your positionality. The assumptions you surface (or miss) depend on your perspective. And your role choice — instructor vs facilitator vs co-designer — is an expression of how you relate to the system and the learners. These three topics form a coherent unit about "what change you intend and how your position shapes that intent."

**Why they don't belong with system mapping:** System mapping is about understanding what exists. Theory of Change is about articulating what you intend. They are related but distinct thinking moves. Separating them lets the reader do one well before starting the other.

### New Lesson 3: Understanding Your Learners

**Source:** Current Lesson 2, unchanged

**Covers:** Primary/secondary audiences, needs assessment, learner realities, barriers, designing with learners

**Activities:** Activity 3 (Learner Reality Mapping)

**Why unchanged:** This lesson is well-scoped and concise (~800 words). It has a clear focus and doesn't repeat material from other lessons.

### New Lesson 4: How People Learn

**Source:** Current Lesson 3, unchanged

**Covers:** Cognitive load, retrieval and active recall, spacing and reinforcement, social learning

**Activities:** Activity 4 (Learner Experience Audit), revisit Activity 3

**What changes:**
- **Add** a nuance on cognitive load: cognitive load is not always a bad thing. The lesson currently frames cognitive load as something to reduce, but productive struggle — the feeling of genuinely grappling with a concept — is where deep learning happens. If learners always feel comfortable, they may not be learning much. The goal is to manage cognitive load so it comes from engaging with the material itself (intrinsic load), not from poor design (extraneous load). Readers need to understand this distinction so they don't over-simplify their training in the name of "reducing load."

**Why mostly unchanged:** This lesson is well-scoped (~900 words) and covers learning science clearly. The important change is that this becomes the **single authoritative source** for these concepts. Later lessons will reference back to Lesson 4 rather than re-explaining cognitive load or retrieval.

### New Lesson 5: Learning Outcomes and Alignment

**Source:** Current Lesson 4, with an important addition

**Covers:** Learning outcomes, backward design, constructive alignment, design order vs delivery order, Bloom's Taxonomy

**What changes:**
- **Add** a section on the limits of backward design and alignment. The current lesson presents these frameworks as straightforward recipes: define outcomes → design evidence → design activities. That's useful scaffolding, but it can lead to rigid, box-ticking course design — especially for readers new to instructional design who may follow the steps too literally.
- The new content should address:
  - **You will get outcomes wrong.** First-time designers rarely nail their outcomes on the first try. Outcomes are a starting point, not a contract. They should be revisited and revised as the design develops.
  - **Tight alignment can become a trap.** If every activity exists only to tick an outcome box, and every assessment exists only to check that box, you end up with a narrow, mechanical course that leaves no room for the unexpected — which is often where the most valuable learning happens.
  - **Frameworks are thinking tools, not rules.** Backward design and alignment tables are checklists to support your thinking, not recipes to follow rigidly. They help you spot gaps and mismatches, but the goal is a coherent learning experience, not a perfectly filled-in table.
  - **Leave room for emergence.** Good training creates space for learners to surprise you — with questions you didn't anticipate, connections you didn't plan, or needs that only become visible during delivery. A design that is too tightly optimised for predefined outcomes can squeeze this out.

**Activities:** Activity 5 (Learning Outcomes), Activity 6 (Alignment Table)

**Why this addition matters:** Without this counterweight, the lesson risks producing exactly the kind of rigid, outcome-obsessed designs it should help readers avoid. Readers who are new to these frameworks need permission to treat them as guides rather than gospel — and they need to hear that revising outcomes mid-design is a sign of good practice, not failure.

### New Lesson 6: Co-Design and Constraints

**Source:** Current Lesson 5, tightened

**What changes:**
- **Remove** the detailed co-design vs co-creation distinction (current lines 69-101). This section spends significant space defining a difference that only becomes meaningful in the next lesson.
- **Keep** co-design defined simply: participants help shape what the training will be and how it works.
- **Add** a brief forward reference: "In the next lesson, you'll see how learners can contribute within activities — what we call co-creation."
- **Keep everything else:** constraints, trade-offs, meaningful participation, ethical engagement, the example, Activity 7.

**Covers:**
- Who is shaping the training and who should be involved
- Constraints: time, access, infrastructure, language, power, institutional dynamics
- Making trade-offs explicit
- Ensuring participation is meaningful, not tokenistic

**Activities:** Activity 7 (Co-Design Plan), revisit Activity 1

**Why this tightening works:** The co-creation concept is better introduced where it is applied (activity design, next lesson). Removing it here eliminates the overlap with Lesson 6→7 without losing the concept — it just moves to where it makes more sense.

### New Lesson 7: Designing Learning Activities

**Source:** Current Lesson 6, focused

**What changes:**
- **Remove** the re-explanation of cognitive load and retrieval (current lines 73-78). Replace with a cross-reference: "Apply the cognitive load and retrieval principles from Lesson 4 when structuring your activities."
- **Remove** the Activity 9 revisit (current lines 153-158). Activity 9 (Practice & Feedback Plan) belongs in the next lesson, not here.
- **Absorb** the co-creation concept: learners contributing within activities. This was previously split awkwardly between Lessons 5 and 6. Now it lives here, where it is applied.

**Covers:**
- Designing activities from outcomes
- Structuring each activity clearly (objective, instructions, materials, time, output, feedback)
- Designing for inclusive participation (pair work, small groups, think time, multiple contribution modes)
- Co-creation within activities — how learners contribute their knowledge and experience
- Scaffolding and sequencing
- Adapting activities to context

**Activities:** Activity 8 (Learning Activity Design)

**Why this focusing works:** Current Lesson 6 tries to do too much: activity design + co-creation + scaffolding + learning science recap + participation + adaptation + Activity 9. By removing the repeated learning science and the misplaced Activity 9 reference, the lesson narrows to one question: "How do you design a well-structured, participatory activity?"

### New Lesson 8: Practice, Feedback, and Iteration

**Source:** Current Lesson 7, unchanged

**Covers:** Practice types (guided, independent, collaborative), feedback design, making feedback useful, iteration and versioning, peer learning

**Activities:** Activity 9 (Practice & Feedback Plan), revisit Activity 8

**Why unchanged:** This lesson is well-scoped. The key improvement is that Activity 9 now has a **single clear home** here, rather than being referenced in both Lessons 6 and 7. The boundary with New Lesson 7 is now clean: Lesson 7 answers "What will learners do?" and Lesson 8 answers "How will they improve at it?"

### New Lesson 9: Assessment for Learning

**Source:** Current Lesson 8, first half (core concepts intro, Steps 1-3), with significant reframing

**Covers:**
- What assessment is — focused on what learners know, produce, decide, or do
- Defining what success looks like — clear, observable indicators
- Designing assessment aligned with outcomes and activities (tasks, outputs, decisions, methods)
- Formative assessment (during learning) and summative assessment (at end)

**What changes — reframe assessment as a learning tool, not a measuring tool:**

The current lesson treats assessment primarily as a way to check whether learning happened. This is accurate but incomplete, and it risks reinforcing the very association most readers already have: assessment = judgement, grades, anxiety.

The reframed lesson should establish:

- **Assessment serves the learner and the trainer.** Low-stakes assessments help learners see where their gaps are. They also give you feedback about where your training is falling short. Assessment is a two-way mirror, not a one-way judge. This point deserves real emphasis: when learners consistently struggle with a concept, that is information about your teaching, not just about their learning. Trainers who treat assessment as feedback on their own practice — not just as a learner scorecard — improve faster and design better training over time.
- **Assessment should be paired with support and curiosity, not anxiety.** Many people's experience of assessment is formal, high-stakes, and anxiety-provoking. This workbook's audience is designing practical training, not academic courses. The lesson should actively counter the "harsh judge" framing and position assessment as a tool for growth and honest self-reflection.
- **Activities can be assessments — you don't need a separate exam.** If a learner completes a well-designed activity that demonstrates a skill, that is evidence of learning. You don't need a separate "test" bolted on. This connects back to Lesson 7 (activity design) — a good activity already generates evidence of what learners can do. The lesson should make this feel like a liberation, not a concession: for practical training in resource-constrained settings, observing what learners produce during activities is often more valid evidence than any formal test could be.
- **Avoid overly formal academic assessment.** Formal exams, rubrics, and grading scales are not the default here. The standard exam is not something readers should aspire to replicate — it exists for institutional contexts with very different needs. The goal is methods that help people learn and help trainers teach — not boxes to tick. Choose assessment approaches that fit the context and serve the learners, not ones borrowed from university settings because they feel "proper."

**Activities:** Activity 10 (Assessment Plan — renamed from "Assessment & Evaluation Plan"), revisit Activity 6 (Alignment Table — check assessments reflect intended outcomes)

**Why this works as a Part 1 closer:** Assessment completes the design arc. By Lesson 9, the reader has: mapped their system (L1), articulated intended change (L2), understood their learners (L3), grounded their design in learning science (L4), defined outcomes and alignment (L5), incorporated co-design and constraints (L6), designed activities (L7), built in practice and feedback (L8), and now designed assessment to make learning visible (L9). That is a complete, coherent training design.

---

## Extra Topics

These topics sit outside the main Part 1 and Part 2 sequences. They are important for practitioners but are not part of the core design-to-OER workflow.

### Extra Topic: Facilitation, Delivery, and Session Structure

**Source:** New content

**Why this exists:** The workbook teaches design but not delivery. First-time trainers need practical guidance on what happens when they stand up in front of a room. This gap is critical — a well-designed training can fail completely with poor facilitation — but facilitation is not part of the design workflow itself. It is a complementary skill set.

**Covers:**
- Session structure — opening (framing the session, setting expectations), transitions between activities, closing (reflection, what comes next)
- Time management — realistic time planning, what to cut when you run over (because you will), buffer time, the difference between design time and real time
- Reading the room — recognising confusion, fatigue, disengagement, and what to do about each
- Group dynamics — dominant voices, quiet participants, conflict, managing power dynamics in the room (connecting back to positionality from Lesson 2)
- Working with co-facilitators and interpreters — division of roles, handoffs, real-time coordination
- When things go wrong — technology failure, content that doesn't land, running out of time, unexpected emotional responses. Practical contingency thinking, not panic
- Multi-session programme structure — sequencing sessions across a day or multiple days, logistics (room setup, materials prep), energy management across a full day
- Emotional readiness — normalising nervousness for first-time trainers, giving permission to not know everything, preparation as structure and flexibility rather than memorising content

**Activities:** New activity — Facilitation and Session Plan (readers plan the structure, timing, and facilitation approach for at least one session of their training, including logistics, contingency plans, and role assignments if co-facilitating)

**What this is NOT:** A standalone facilitation textbook. The scope is "enough to get a first-time trainer through their first delivery with reasonable confidence." Practical, short, focused on decisions and common failure modes.

### Extra Topic: Evaluation for Impact

**Source:** Current Lesson 8, second half (Steps 4-6)

**Covers:**
- What evaluation is — understanding change over time, beyond the training event
- Collecting useful and feasible evidence (observation, outputs, reflections, follow-up, peer/facilitator review)
- Focusing on signal, not noise — distinguishing meaningful change from weak or easy indicators
- Using evaluation to improve — refining activities, identifying gaps, improving future delivery
- Connection back to Theory of Change from Lesson 2 — you started by articulating what change you hoped for, and now you're asking whether the training contributed to it

**Activities:** New activity — Evaluation Plan (readers define what evidence they will collect, when, from whom, and how they will use it to improve. This was previously bundled with assessment in Activity 10)

**Why this moved out of Part 1:** Evaluation looks forward — beyond the training event to longer-term change. It answers "Did the training contribute to real-world impact?" rather than "Did learners learn what we intended?" That is a valuable question, but it is not part of the design workflow. It requires the training to have been delivered (or at least planned for delivery) before it becomes actionable. Placing it in Extra Topics signals that it matters without forcing it into a design sequence where it sits awkwardly.

**Note on the Part 2 bridge:** The current Lesson 8 contains a "Bridging to Part 2" section. This transition content should move to the Part 1 closing (index page or a short closing section after Lesson 9), not into the Evaluation extra topic.

---

## Summary of changes

| What | Action |
|---|---|
| Current Lesson 1 | Split into New Lessons 1 and 2 |
| Current Lesson 2 | Renumber to Lesson 3, no content changes |
| Current Lesson 3 | Renumber to Lesson 4, no content changes |
| Current Lesson 4 | Renumber to Lesson 5, add section on limits of backward design |
| Current Lesson 5 | Renumber to Lesson 6, remove co-creation detail, add forward reference |
| Current Lesson 6 | Renumber to Lesson 7, remove learning science repetition, remove Activity 9 reference |
| Current Lesson 7 | Renumber to Lesson 8, no content changes |
| Current Lesson 8 | Split: assessment → New Lesson 9; evaluation → Extra Topic; bridge to Part 2 → Part 1 closing |
| New content | Extra Topic: Facilitation, Delivery, and Session Structure |
| New content | Extra Topic: Evaluation for Impact |

---

## Learning outcome accounting

All 41 original learning outcomes are preserved. None are lost. New outcomes are added for the facilitation topic.

| Original Lesson | Outcomes | New Home |
|---|---|---|
| L1: Describe training as intervention; identify system elements | 2 | New L1 |
| L1: Theory of change; positionality; assumptions/risks | 3 | New L2 |
| L2: All 5 outcomes (learner analysis) | 5 | New L3 |
| L3: All 5 outcomes (learning science) | 5 | New L4 |
| L4: All 5 outcomes (outcomes and alignment) | 5 | New L5 |
| L5: All 5 outcomes (co-design and constraints) | 5 | New L6 |
| L6: All 6 outcomes (activity design) | 6 | New L7 |
| L7: All 5 outcomes (practice/feedback/iteration) | 5 | New L8 |
| L8: Distinguish assessment vs evaluation | 1 | New L9 (introduced) and Extra Topic: Evaluation (deepened) |
| L8: Formative/summative assessments; observable indicators | 2 | New L9 |
| L8: Evidence collection methods; signal vs noise | 2 | Extra Topic: Evaluation for Impact |

**Original outcomes: 41 in → 41 preserved**

**New outcomes (Extra Topic: Facilitation, Delivery, and Session Structure):**

- Plan session structure including opening, transitions, and closing
- Manage time realistically, including contingency plans for when things run over
- Recognise and respond to common group dynamics (dominant voices, disengagement, conflict)
- Adapt facilitation approach in real time based on what is happening in the room
- Coordinate with co-facilitators or interpreters to deliver training effectively

**Total with new: 41 original + 5 new = 46**

---

## Activity placement

| Activity | Primary Home | Revisited In |
|---|---|---|
| 1. System Map | New L1 | New L6 |
| 2. Theory of Change | New L2 | — |
| 3. Learner Reality Mapping | New L3 | New L4 |
| 4. Learner Experience Audit | New L4 | — |
| 5. Learning Outcomes | New L5 | — |
| 6. Alignment Table | New L5 | New L9 |
| 7. Co-Design Plan | New L6 | — |
| 8. Learning Activity Design | New L7 | New L8 |
| 9. Practice & Feedback Plan | New L8 | — |
| 10. Assessment Plan (renamed) | New L9 | — |
| 11. Facilitation and Session Plan (new) | Extra Topic: Facilitation | — |
| 12. Evaluation Plan (new) | Extra Topic: Evaluation | — |
| 13. Training Design Snapshot (was 11) | Part 2 | — |
| 14. OER Workflow (was 12) | Part 2 | — |

**Key changes from original plan:**

- Activity 9 now has one home (New L8) instead of being referenced in both current L6 and L7.
- Activity 10 renamed from "Assessment & Evaluation Plan" to "Assessment Plan" — scoped to assessment only.
- Activity 6 (Alignment Table) revisit moves to New L9, where it directly supports checking assessment alignment.
- New Activity 11 (Facilitation and Session Plan) added for the facilitation extra topic.
- New Activity 12 (Evaluation Plan) split out from old Activity 10 for the evaluation extra topic.
- Part 2 activities renumbered: Training Design Snapshot becomes Activity 13, OER Workflow becomes Activity 14.

---

## How to apply each lesson

Each lesson must be run through the **lesson skill** (`.claude/skills/lesson`) as it is created or edited. This means every lesson produced by this refactoring must conform to the lesson anatomy, formatting rules, and quality checklist defined in that skill — not just the structural changes described above.

In practice, for each lesson:

1. Make the structural change described in this plan (split, renumber, add/remove content, etc.)
2. Apply the lesson skill: ensure the result has correct frontmatter, opening, "Why this matters", body with methods and examples, "In practice" activity links, and "Before you move on" outputs
3. Apply the voice-and-tone skill to all prose (the lesson skill requires this)
4. Run through the lesson skill's quality checklist before considering the lesson done

Lessons marked "no content changes" (e.g. current Lessons 2, 3, 7) still need to be checked against the lesson skill — renumbering alone is not sufficient if the existing content doesn't meet the skill's standards.

---

## How to apply each activity

Each activity must be run through the **activity skill** (`.claude/skills/activity`) as it is created or edited. This means every activity produced by this refactoring must conform to the activity anatomy, formatting rules, and quality standards defined in that skill.

In practice, for each activity:

1. Make the structural change described in this plan (renumber, fix references, split, create, etc.)
2. Apply the activity skill: ensure the result has correct frontmatter (`used_in`, `what_to_do`, `expected_output`, `approximate_time`), header include, instructions, and a core task producing a concrete artefact
3. Verify cross-reference integrity:
   - "You will use" references only EARLIER activities with correct numbers, titles, and file paths
   - "Reuse in later sections" references only LATER activities with correct numbers, titles, and file paths
   - No `[TODO]` placeholders remain anywhere
4. Verify section ordering matches the activity skill (Reflection before forward-looking sections like "Reuse in later sections")
5. Apply the voice-and-tone skill to all prose
6. Run through the activity skill's quality standards before considering the activity done

Activities marked "no content changes" still need full skill compliance checked — the existing content has cross-reference errors and structural issues that predate this refactoring.

---

## Activity changes in detail

A review of all Part 1 activities surfaced widespread cross-reference errors, TODO placeholders, and structural issues. These must be fixed as part of the refactoring.

### Wrong cross-references in "You will use"

| Activity | Current reference | Should be | Why |
|---|---|---|---|
| 4 (Learner Experience Audit) | "Activity 2" (×2) | Activity 3 (Learner Reality) | Activity 2 is Theory of Change, not learner realities |
| 5 (Learning Outcomes) | "Activity 4" | Activity 2 (Theory of Change) | Activity 4 is Learner Experience Audit, not ToC |
| 5 (Learning Outcomes) | "Activity 2" for learner constraints | Activity 3 (Learner Reality) | Same mislabel as Activity 4 |
| 6 (Alignment Table) | "Activity 7" | Remove — keep only Activity 5 | Forward reference violation: Activity 7 doesn't exist when Activity 6 is first completed in Lesson 5. The alignment table starts incomplete; Activity and Assessment columns are filled in when revisited in Lesson 9 |
| 10 (Assessment Plan) | "Activity 7" for practice/feedback | Activity 9 (Practice & Feedback) | Activity 7 is Co-Design Plan, not practice/feedback |

### Wrong cross-references in "Reuse in later sections"

| Activity | Current reference | Should be |
|---|---|---|
| 6 (Alignment Table) | "Activity 8 (Evaluation Plan)" | Activity 10 (Assessment Plan) |
| 6 (Alignment Table) | "Activity 9 (Training Snapshot)" | Activity 13 (Training Design Snapshot) |
| 8 (Learning Activity Design) | "Activity 9 (Evaluation Plan)" | Activity 9 (Practice & Feedback Plan) |
| 8 (Learning Activity Design) | "Activity 10" linking to snapshot file | Activity 13 (Training Design Snapshot) with correct path |
| 9 (Practice & Feedback) | "Activity 10 (Assessment & Evaluation Plan)" | Activity 10 (Assessment Plan) — updated name |
| 10 (Assessment Plan) | "Activity 11 (Training Snapshot)" | Activity 13 (Training Design Snapshot) — add Activity 12 (Evaluation Plan) |

### [TODO] placeholders that must be resolved

| Activity | Location | Resolution |
|---|---|---|
| 3 (Learner Reality) | "Reuse in later sections" | Referenced by Activities 4, 7, 8, and 13 |
| 5 (Learning Outcomes) | "Reuse in later sections" | Referenced by Activities 6, 8, 9, and 10 |
| 7 (Co-Design Plan) | "Reuse in later sections" | Referenced by Activity 8 (co-design decisions inform activity design) |
| 13 (Snapshot, was 11) | `used_in` frontmatter | Should reference the Part 2 lesson that uses it |

### Wrong references in body text

| Activity | Line | Current | Should be |
|---|---|---|---|
| 5 (Learning Outcomes) | 34 | "Activity 2" | Activity 3 (Learner Reality) |
| 8 (Learning Activity Design) | 34 | "Activity 2" | Activity 3 (Learner Reality) |
| 13 (Snapshot, was 11) | 43 | "Activity 2" for learner constraints | Activity 3 (Learner Reality) |
| 13 (Snapshot, was 11) | 45 | "Activity 7" for core activity | Activity 8 (Learning Activity Design) |
| 13 (Snapshot, was 11) | 46 | "Activity 8" for evaluation | Activity 10 (Assessment Plan) + Activity 12 (Evaluation Plan) |
| 13 (Snapshot, was 11) | 84 | "Activity 10" for OER | Activity 14 (OER Workflow) |

### Structural changes

- **Activity 10:** Rename from "Assessment & Evaluation Plan" to "Assessment Plan". Remove evaluation columns from the table ("Signal vs noise", "Evaluation (after training)"). Remove evaluation references from Diagnose and Improve sections. Rename file to `activity_10_assessment.md`.
- **New Activity 11 (Facilitation and Session Plan):** Create for Extra Topic: Facilitation. Artefact: a structured facilitation plan for one session. "You will use" references Activities 5, 8, and 9.
- **New Activity 12 (Evaluation Plan):** Create for Extra Topic: Evaluation. Content split from old Activity 10's evaluation scope. "You will use" references Activities 2, 5, and 10.
- **Activity 13 (Snapshot, was 11):** Rename file from `activity_11_snapshot.md` to `activity_13_snapshot.md`. Add missing frontmatter fields (`what_to_do`, `expected_output`, `approximate_time`).
- **Activity 14 (OER Workflow, was 12):** Rename file from `activity_12_oer.md` to `activity_14_oer.md`.

### Section ordering fixes

Activities 6, 8, 9, and 10 all have Reflection placed after "Reuse in later sections". The activity skill expects Reflection before forward-looking sections. Reorder during skill application.

### Frontmatter updates (all activities)

Every activity's `used_in` field references old lesson file paths and titles. All must be updated to match new lesson numbers:

| Activity | Old `used_in` lesson | New `used_in` lesson(s) |
|---|---|---|
| 1 (System Map) | Lesson 1 | Lesson 1 (primary), Lesson 6 (revisit) |
| 2 (Theory of Change) | Lesson 1 | Lesson 2 |
| 3 (Learner Reality) | Lesson 2, Lesson 3 | Lesson 3 (primary), Lesson 4 (revisit) |
| 4 (Learner Experience Audit) | Lesson 3 | Lesson 4 |
| 5 (Learning Outcomes) | Lesson 4 | Lesson 5 |
| 6 (Alignment Table) | Lesson 4 | Lesson 5 (primary), Lesson 9 (revisit) |
| 7 (Co-Design Plan) | Lesson 5 | Lesson 6 |
| 8 (Learning Activity Design) | Lesson 6 | Lesson 7 (primary), Lesson 8 (revisit) |
| 9 (Practice & Feedback) | Lesson 7 | Lesson 8 |
| 10 (Assessment Plan) | Lesson 8 | Lesson 9 |

---

## Files that would need to change

### Part 1 lesson files
1. `docs/part-1/lesson-1.md` — split into two files
2. All lesson files `lesson-2.md` through `lesson-8.md` — renumber to `lesson-3.md` through `lesson-9.md`
3. New `lesson-2.md` — created from second half of current lesson-1
4. New `lesson-6.md` (current L5) — remove co-creation detail, add forward reference
5. New `lesson-7.md` (current L6) — remove learning science repetition, remove Activity 9 revisit
6. Current `lesson-8.md` — narrow to assessment only (New Lesson 9), move evaluation content out
7. `docs/part-1/index.md` — update lesson list to 9 entries, add bridge-to-Part-2 content (moved from old Lesson 8)

### Extra Topics (new section)
8. New directory and index: `docs/extra-topics/index.md`
9. New file: `docs/extra-topics/facilitation.md`
10. New file: `docs/extra-topics/evaluation.md`

### Activities

**Structural changes:**
11. `activity_10_assess_evaluate.md` — rename to `activity_10_assessment.md`, narrow to assessment only, remove evaluation columns and references
12. New: `activity_11_facilitation_session_plan.md` — facilitation and session plan for Extra Topic
13. New: `activity_12_evaluation_plan.md` — evaluation plan split from old Activity 10, for Extra Topic
14. Rename `activity_11_snapshot.md` → `activity_13_snapshot.md` — fix all internal cross-references, add missing frontmatter fields
15. Rename `activity_12_oer.md` → `activity_14_oer.md`

**Cross-reference and compliance fixes (all activities):**
16. Activities 1–10 — update `used_in` frontmatter to new lesson numbers and file paths
17. Activities 4, 5 — fix wrong activity numbers in "You will use" (stale references to Activity 2 that should be Activity 3)
18. Activity 6 — remove forward reference to Activity 7 in "You will use", keep only Activity 5
19. Activity 10 — fix "You will use" reference from Activity 7 to Activity 9
20. Activities 3, 5, 7 — resolve `[TODO]` in "Reuse in later sections"
21. Activities 6, 8, 9, 10, 13 — fix wrong activity numbers/labels in "Reuse in later sections"
22. Activities 5, 8, 13 — fix wrong activity numbers in body text
23. Activities 6, 8, 9, 10 — reorder Reflection before "Reuse in later sections"
24. `docs/activities/index.md` — update activity list: rename Activity 10, add Activities 11–12, renumber 13–14

**Apply activity skill to every touched file.**

### Configuration and cross-references
25. `mkdocs.yml` — update nav section: Part 1 with 9 lessons, new Extra Topics section
26. All lesson and activity files — update any "Lesson N" cross-references to match new numbering
27. All activity files — update any "Activity N" cross-references to match new numbering
