# Atobi Actions

**Atobi · 2024 · Sole Designer**

`EdTech` `Retail` `Mobile PWA`

---

## Context & Problem

Atobi is a mobile-first learning platform used by retail staff — frontline workers who need to stay current on product knowledge, brand standards, and operational procedures. The existing training format (called Missions) had low completion rates and a structure that didn't fit how retail workers actually operate: in short bursts, frequently interrupted, often mid-shift.

The brief was to redesign the training module experience. What emerged went further — a new content format that got adopted beyond training for operational documentation.

---

## My Role & Scope

I was the sole designer. I owned the end-to-end design process: research (within the constraints available), concept development, interaction design, and handoff. I worked directly with the product manager and engineering team throughout.

There was no design team. Decisions were made collaboratively with the PM, but the design work was mine alone.

---

## Constraints & Reality

**Limited direct user access.** Atobi's end users are retail store staff — a population that's difficult to reach for research. Recruiting was slow and access was restricted. I had to work with secondary sources: analytics, internal feedback from customer success, and input from a small number of client contacts. This shaped how I validated decisions.

**PWA constraints on interaction design.** The product runs as a Progressive Web App, not a native app. Certain animations and transitions that would have been straightforward in native iOS or Android weren't feasible. I had to find ways to create a quality interaction feel within those limits.

**Gamification tension.** Retail learning platforms often lean heavily on gamification — streaks, points, badges. The business had appetite for it. But frontline workers are at work, not playing a game. Gamification that feels appropriate in a consumer app can feel patronising in a professional context. I had to navigate that tension explicitly.

**Restricted content access for research.** I couldn't always access live production content to understand what users were actually encountering. Some assumptions about the content structure had to be confirmed through stakeholder input rather than direct observation.

---

## Key UX Challenges

**1. Interrupted sessions were the norm, not the exception**
Retail workers don't sit down and complete a training module. They start something, get pulled away, come back later. The existing module format didn't account for this — returning to a partially completed Mission was confusing and demotivating.

**2. Articles and Actions were separate — they shouldn't be**
The original structure separated reading content from interactive tasks. In practice, users needed both in the same workflow. The artificial split created friction and made modules feel longer and more effortful than they were.

**3. Making interactivity feel native on a PWA**
The redesigned format relied on interactive elements — taps, swipes, embedded questions. Getting those to feel fluid on a PWA required careful scoping of what was technically achievable and creative workarounds where native-quality interaction wasn't possible.

**4. Defining the right role for gamification**
Points and progress indicators have a real function — they signal completion and reward effort. But the implementation mattered. Applied poorly, gamification undercuts the professional tone the platform needed to maintain.

---

## Design Approach & Decisions

**Merging articles and interactive Actions into a single format**
The core design decision was to combine reading content and interactive tasks into one unified module type — Actions. Instead of switching between a reading view and a tasks view, users move through a single, mixed-content flow. This reduced cognitive friction and made modules feel shorter even when the content volume was the same.

**Action Mode for interrupted sessions**
The biggest insight from user research and analytics was that interruption wasn't an edge case — it was the dominant pattern. I designed Action Mode as an explicit response to this: a focused, minimal view that strips away navigation and context so a returning user can re-orient and continue quickly. The assumption that users would complete modules in one session was wrong, and the design needed to stop making that assumption.

**PWA-first interaction decisions**
Rather than designing for an ideal native experience and then compromising, I scoped the interaction model around what the PWA could actually deliver well. Some transitions were simplified. Some animations were cut. The constraint became part of the design brief, not a problem to solve later.

**Restrained gamification**
I kept progress indicators but removed anything that felt more at home in a consumer game than a work tool. The argument to the business was that trust and relevance matter more to long-term engagement than short-term dopamine loops. That case was supported by the data that emerged post-launch.

---

## Trade-offs & What I Didn't Do

**Research depth was limited — and that's worth naming.**
The access constraints meant validation was thinner than I would have wanted. I compensated by leaning harder on analytics and internal feedback, and by designing for flexibility so assumptions could be corrected quickly after launch. It's not the same as robust user research, and I know that.

**Gamification was reduced, not removed.**
I argued against heavy gamification but didn't eliminate it. There was legitimate business appetite for it and some user segments respond positively. The final design reflects a compromise — present but restrained.

**The scope expanded without being formally planned.**
Actions were later adopted beyond the training context — for operational documents and announcements. That's a good outcome, but it was emergent rather than designed. With more runway, I would have explored that broader use case deliberately.

---

## Outcome & Impact

- **7% increase in app adoption** following launch
- **387% increase in response rate** compared to the previous Missions module
- Actions were subsequently adopted beyond training for operational documentation — a scope expansion that emerged organically from how teams actually used the format

---

## Learnings & Reflections

**Design for the real behaviour, not the intended behaviour.** The interrupted-session pattern was there in the data before I started. The original design had just chosen to ignore it. Naming that honestly and designing around it was the most important decision in the project.

**Constraints are part of the brief.** PWA limitations, restricted user access, gamification pressure — none of these were ideal. But treating them as design inputs rather than obstacles produced a more grounded outcome than trying to design around them would have.

**An honest constraint is better than a polished gap.** I would have preferred more direct user access during this project. I didn't have it, and I've built different habits since — pushing harder for access earlier, and being explicit with stakeholders about what validation is and isn't in scope. Naming the limitation isn't a weakness in the case study. Pretending it didn't exist would be.
