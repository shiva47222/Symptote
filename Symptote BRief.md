# Symptote — Project Brief

## Name & Concept

The project is called **Symptote**, derived from the Greek root *sympiptein* — meaning "falling together." It is the conceptual opposite of an *asymptote* (from *asymptotos*, "not falling together").

The piece lives as a coded artwork embedded in a personal website built on Google Sites with a custom domain (hosted via GitHub Pages).

---

## What It Represents

Two people who are meant to meet. The piece maps their journey through a 2D mathematical space — not as a romantic abstraction, but as an honest one: convergence is not guaranteed by the math, only by something beyond it. And even after meeting, the future is open.

---

## The Space

- **X-axis — time.** The leftmost point (x = 0) is birth. Time moves rightward.
- **Y-axis — physical distance** between the two people (for now; may expand to other kinds of distance later).
- **A horizontal asymptote** divides the canvas exactly in half. This line separates two worlds — one above, one below. Each person lives in their own world.

---

## The Curves

- Each person is represented by a curve that begins at birth (t = 0) far from the asymptote and tends toward it over time — a true asymptotic decay, mathematically never crossing.
- The two curves are **symmetric** in this version, mirroring each other across the asymptote.
- In future versions, the curves will **fluctuate** — drifting closer to and farther from the asymptote over time, reflecting whatever happens in each person's life. Only after periods of fluctuation do they begin their final, committed approach toward the dividing line.
- At a specific point in time, the curves **break the mathematical rule** — they meet at the asymptote. This is the moment of convergence.

---

## The Meeting Point

- The meeting point is **interactively adjustable** — the viewer can drag it or use a slider to place it anywhere along the timeline.
- At the moment of meeting, everything changes immediately:
  - The **asymptote dissolves** (the dashed dividing line ends).
  - The **two curves merge into a single line**, coloured as an immediate mix of both individual colours.
  - The **two world backgrounds merge immediately** into a single blended colour — no gradual fade, an instant unification.
  - The merged line continues forward as one.

---

## After They Meet

The single merged line does not imply permanence. Future versions will allow:
- The line to **continue together** indefinitely
- The line to **separate** into two again at some point
- The line to **re-merge** after separating
- All of the above at different times — reflecting the honest complexity of togetherness

---

## Aesthetic

- **Warm and emotional** — soft colours, not clinical or cold
- Upper world: warm tones (amber/terracotta)
- Lower world: cool tones (blue/indigo)
- Merged world: an immediate blend of both
- Line colours follow the same logic — each person has their own colour, the merged line is their mix
- Supports both **light and dark mode**
- Minimal UI — axes are subtle, labels are quiet, the piece speaks for itself

---

## Version History

| Version | What changed |
|---|---|
| v1 | Basic canvas: two worlds, two curves approaching an asymptote, single merged line after meeting |
| v2 | Fixed curves to be mathematically asymptotic (true decay from birth at t=0); birth marker added |
| v3 | Post-meeting world backgrounds blend; merged line colour oscillates between both person colours |
| v4 | Immediate colour mix at meeting point (backgrounds + line); meeting point made interactively adjustable via slider and canvas drag |

---

## Planned Next Steps

1. **Fluctuation phase** — before their final convergence, both curves drift closer and farther unpredictably, only eventually committing to tending toward the asymptote
2. **Animation** — the curves draw themselves over time, telling the story as it unfolds
3. **Post-meeting behaviour** — the merged line can separate, re-merge, or continue; the piece becomes a full life arc
4. **Refinement** — dissolve the asymptote line more gracefully at the meeting point; explore richer background transitions

---

## Technical Notes

- Built in plain HTML/CSS/Canvas (no frameworks or dependencies)
- Self-contained single `.html` file — `symptote.html` (rename to `index.html` for GitHub Pages)
- Hosted on **GitHub Pages**, embedded into Google Sites via **Insert → Embed → By URL**
- Domain managed through **Namecheap** (domain only, no hosting plan)
- To continue: paste the latest `symptote.html` code into a new Claude conversation alongside this brief
