# Audience Workstream — Content Engine Repo

**Timidlly × Ladder cohort · Weeks 2–8 · Maintained by Dũng**

This repo is the single home for everything the Audience track produces: the spec, the baseline numbers, the content calendar, and every batch that ships. If someone else had to run this track from scratch, this repo should be enough (that's the Week 7 test).

## Structure

```
audience-repo/
├── README.md          ← you are here
├── docs/              ← spec, engine workflow, cadence plan, weekly reports
├── templates/         ← repurposing-kit.md — the prompts that run the engine
├── baseline/          ← reach-baseline-tracker.xlsx — single source of truth for numbers
├── calendar/          ← content-calendar.csv — plan + status of every piece
├── batches/           ← every batch: source piece + all platform drafts (batch-001, 002, ...)
└── published/         ← mirror of shipped batches + links, by week
```

## Weekly rhythm

1. **Plan** — add the week's pieces to `calendar/content-calendar.csv` (status: Idea)
2. **Produce** — move pieces through Drafted → Approved → Published
3. **Ship** — drop links/copies of published work into `published/week-N/`
4. **Measure** — after ~7 days, fill in Reach and Engagement columns in the calendar; log channel-level numbers in `baseline/` Update Log at Weeks 5, 6, and 8
5. **Report** — Friday checks and weekly reports go in `docs/`

## Key documents

- `docs/content-engine-scope.md` — the Week 2 spec: goals, audience, channels, workflow, KPIs
- `docs/engine-workflow.md` — the Week 3 skeleton: pipeline stages, quality checklist, rules
- `templates/repurposing-kit.md` — master prompt + platform adapters (how batches get made)
- `docs/cadence-plan.md` — the Week 4 cadence: N, weekly rhythm, definition of "running"
- `baseline/reach-baseline-tracker.xlsx` — Week 2 baseline every future delta is measured against

## Notes

- Numbers should match Hyeonseok's media-kit dashboard — one source of truth, agreed together.
- Keep a personal copy of this repo synced somewhere you control; it doubles as your portfolio of the internship.
