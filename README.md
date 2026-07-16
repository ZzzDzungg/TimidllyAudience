# Audience Workstream — Content Engine Repo

**Timidlly × Ladder cohort · Weeks 2–8 · Maintained by Dũng**

This repo is the single home for everything the Audience track produces: the spec, the baseline numbers, the content calendar, and every batch that ships. If someone else had to run this track from scratch, this repo should be enough (that's the Week 7 test).

## Structure

```
audience-repo/
├── README.md          ← you are here
├── docs/              ← content-engine spec, weekly reports, workflow docs
├── baseline/          ← reach-baseline-tracker.xlsx — single source of truth for numbers
├── calendar/          ← content-calendar.csv — plan + status of every piece
└── published/         ← links or copies of every shipped batch, by week
```

## Weekly rhythm

1. **Plan** — add the week's pieces to `calendar/content-calendar.csv` (status: Idea)
2. **Produce** — move pieces through Drafted → Approved → Published
3. **Ship** — drop links/copies of published work into `published/week-N/`
4. **Measure** — after ~7 days, fill in Reach and Engagement columns in the calendar; log channel-level numbers in `baseline/` Update Log at Weeks 5, 6, and 8
5. **Report** — Friday checks and weekly reports go in `docs/`

## Key documents

- [`ContentEngineScope.md`](ContentEngineScope.md) — the Week 2 spec: goals, audience, channels, workflow, KPIs (will move to `docs/` once the folder scaffold is in place)
- `baseline/reach-baseline-tracker.xlsx` — Week 2 baseline every future delta is measured against (not yet added to the repo)

## Notes

- Numbers should match Hyeonseok's media-kit dashboard — one source of truth, agreed together.
- Keep a personal copy of this repo synced somewhere you control; it doubles as your portfolio of the internship.
