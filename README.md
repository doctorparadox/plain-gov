# plain-gov

Just the facts, ma'am — original sources and canonical information about the workings of government, with no partisan reindeer games.

**plain-gov** is a set of plain-text structural maps of the U.S. federal government: how the branches are organized, and how the core processes actually run. Each map is a single monospace ASCII file — no images, no JavaScript, no tracking. They render anywhere a fixed-width font does: a terminal, a code viewer, a text box, a printout. They diff cleanly, so every change to a chart is visible line by line.

The goal is civic literacy you can read in five minutes and trust: structure over spin, mechanism over narrative.

## How to read the maps

The maps use a small, consistent set of box-drawing symbols:

```
■        the root / top of the structure
├─  └─   a branch (└─ is the last item under its parent)
│        a vertical connector
◆        a major node or stage
▲        appeals / authority flowing upward
──▶      the main path (in a process flow)
└─▶      a branch or bypass off the main path
◇        a decision point ("if X, then…")
✕        the process stops / a door is closed
★        a legally operative result (a ruling, an outlay, a decision)
(acting) / [bracketed]   acting official · dated caveat
```

The **tree** and **org-chart** maps show *structure* (which bodies sit under which). The **process-flow** maps show *sequence* (how something moves from start to finish, including where it can stall or branch).

> **A note on the `[[double brackets]]`:** these maps are exported from an Obsidian knowledge base, where `[[Some Term]]` is an internal cross-reference link. The brackets are left in as a lightweight "see also" marker — the term inside is a real, nameable thing worth looking up. They carry no formatting meaning here.

## The maps

**Structure (trees & org charts)**

- [`congressional-committees-tree.md`](congressional-committees-tree.md) — the standing committees of the House and Senate
- [`executive-branch-ascii-map.md`](executive-branch-ascii-map.md) — the executive branch, from the President down through the departments
- [`federal-judiciary-ascii-map.txt`](federal-judiciary-ascii-map.txt) — the federal courts: Supreme Court → 13 circuits → 94 districts
- [`dhs-components-ascii-map.txt`](dhs-components-ascii-map.txt) — the Department of Homeland Security and its component agencies
- [`us-intelligence-community-ascii-map.txt`](us-intelligence-community-ascii-map.txt) — the intelligence community by parent department
- [`federal-reserve-system-tree.txt`](federal-reserve-system-tree.txt) — the Fed: Board of Governors, 12 regional banks, and the FOMC

**Process (how things actually happen)**

- [`appropriations-pipeline-flow.txt`](appropriations-pipeline-flow.txt) — how federal money moves from authorization to outlay
- [`appropriations-bills-what-each-funds.txt`](appropriations-bills-what-each-funds.txt) — the twelve appropriations bills and what each one funds
- [`confirmation-pipeline-flow.txt`](confirmation-pipeline-flow.txt) — how a presidential nominee is confirmed (or isn't)
- [`executive-order-lifecycle-flow.txt`](executive-order-lifecycle-flow.txt) — how an executive order is issued and challenged
- [`impeachment-and-removal.txt`](impeachment-and-removal.txt) — impeachment in the House, trial and removal in the Senate
- [`treaty-ratification-flow.txt`](treaty-ratification-flow.txt) — how a treaty is made and ratified
- [`supreme-court-certiorari-flow.txt`](supreme-court-certiorari-flow.txt) — how a case reaches the Supreme Court, from petition to ruling
- [`electoral-college-flow.txt`](electoral-college-flow.txt) — the electoral college, from popular vote to inauguration

*New maps are added over time. Structure is verified against primary sources; where a map names current officeholders or reflects current law, it states the date it reflects.*

## License

Released under [CC0 1.0 Universal](LICENSE) — dedicated to the public domain. Copy it, embed it, remix it, teach from it, no permission or attribution required. If it makes government more legible to someone, it did its job.
