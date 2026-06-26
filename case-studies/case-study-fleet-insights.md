# Fleet Insights 2.0

**Danelec · 2025 · Sole Designer**

`Maritime Tech` `B2B SaaS` `Dashboard Redesign`

---

## Context & Problem

Danelec makes software for the maritime industry — specifically for fleet operators managing vessel performance across large fleets. Fleet Insights is their core product: a platform where fleet managers monitor fuel consumption, vessel health, and operational efficiency.

When I joined, the platform had grown organically over years. Navigation was fragmented. Key features like Diagnostics and Fouling Analysis lived in separate silos despite serving related workflows. Getting to an insight required too many clicks, and first-time users were often lost.

The underlying issue wasn't any single broken feature — it was a product that had been built feature-by-feature without a unified information architecture to hold it together.

---

## My Role & Scope

I was the sole designer on this project, working directly with the product manager and a team of engineers. My scope covered:

- End-to-end redesign of the navigation structure
- Merging the Diagnostics and Fouling modules into a unified experience
- Adapting an existing rebrand into the product UI
- Introducing the first structured user research process at Danelec

I did not have a design team to collaborate with. All decisions went through me, with regular alignment with the PM and engineering leads.

---

## Constraints & Reality

**Users are experts.** Fleet managers and marine engineers are highly technical. They don't need hand-holding — they need fast access to precise data. Any simplification that stripped away professional-grade functionality would have been worse than the original problem.

**No prior research baseline.** There was no existing user insight to build on — only anecdotal feedback and internal assumptions. I was starting from scratch.

**The data model wasn't changing.** The underlying architecture stayed fixed. Design decisions had to work within what engineering could support, not around it.

**A rebrand was happening in parallel.** I had to adapt new brand guidelines for a complex product UI — not just apply them. That required judgment about where brand expression served the product and where it didn't.

**Platform merger was on the table.** There was a longer-term vision to merge Fleet Insights with the Voyage Optimization platform. We explored it, but it was parked — resource constraints made it unrealistic within this project's scope.

---

## Key UX Challenges

**1. Navigation that didn't match how users think**
The existing structure was organized around product features, not user jobs. Fleet managers don't think in system modules — they think in tasks: "What's wrong with this vessel?" or "Show me fuel outliers across the fleet." The IA needed to reflect that.

**2. Too many steps to a useful insight**
Early on I set a benchmark: users should reach a meaningful insight in under one minute. The existing flow made that impossible for most common tasks. Every design decision was tested against it.

**3. Diagnostics and Fouling were separated — they shouldn't be**
These two modules served overlapping workflows. Users would investigate a vessel's engine performance in Diagnostics, then have to navigate elsewhere to check hull fouling data — two things that belong together. The separation added friction without any benefit.

**4. Complexity that couldn't be designed away**
This is a technically complex domain. Some screens are necessarily information-dense. The goal was to make density feel intentional and navigable, not overwhelming — which is a different problem than simplification.

---

## Design Approach & Decisions

**Navigation restructure around user goals**
I restructured the nav from a feature-based hierarchy to one organized around what users are trying to do. This reduced the number of top-level items, made the hierarchy clearer, and was grounded in early interviews with fleet managers — I mapped their most frequent tasks and used that to define the new IA.

**Merging Diagnostics and Fouling**
Rather than maintaining two separate modules with overlapping context, I merged them into a single unified view of vessel health. This required pushing back against one stakeholder who had championed the original split — but the user evidence supported consolidation, and the PM backed the decision.

**Under-1-minute benchmark as a design constraint**
I used this as a working constraint throughout the project, not just a post-hoc measure. Every flow was reviewed against it. It kept conversations focused on real usability rather than feature completeness.

**Introducing user research**
I ran the first structured user research sessions in Danelec's product team — a small sample of 4–5 expert users. The sample was limited, but it changed the way the team talked about design decisions. Once there was observed behaviour on the table, opinions carried less weight.

---

## Trade-offs & What I Didn't Do

**The Voyage Optimization merger was parked.**
The UX case for a unified platform was real — users move between Fleet Insights and Voyage Optimization, and the context-switching is friction. But this was a resourcing and strategy decision, not a design one. I documented the recommendation and flagged it for the roadmap rather than designing speculatively for a scope that wasn't confirmed.

**Some complexity stayed complex.**
Certain screens — particularly multi-vessel comparison views — remain information-dense. I made them more structured, but I didn't simplify them to the point of losing utility. Expert users need the data. The job was to organise it, not hide it.

**Adoption risk was managed separately.**
A redesign at this scale carries change-management risk. Rather than design around it, I worked with the team on user training sessions and walkthrough videos produced alongside launch. That's not UX design work, but it was part of making the design work.

---

## Outcome & Impact

- **30% faster navigation** to key vessel data
- **Under 1 minute to first actionable insight** — benchmark achieved for primary workflows
- **First structured user research** introduced to the product team
- Adoption supported through user training sessions and walkthrough videos at launch

---

## Learnings & Reflections

**Expert users are a gift, if you listen right.** They have strong opinions and high standards. That can feel like resistance, but it's the most useful signal you can get. The key is separating "I want more features" from "this workflow doesn't match how I think."

**Structural decisions are the hardest to make and the most valuable.** The nav restructure and module merge had more impact than any individual screen design. These are the decisions that are easy to underestimate in a portfolio, but they're where the real UX work happened.

**Introducing research changes the room.** Even a small amount of observed user behaviour shifts how stakeholders talk about design. Getting that established at Danelec felt like the most durable thing I left behind.
