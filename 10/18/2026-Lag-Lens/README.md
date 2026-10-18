# Lag Lens

Daily surprise for 2026-10-18. A single-file, offline data visualization for cohort milestones that take time to mature.

## What it is

A milestone with a built-in lag (reach step two within 14 days, come back for a second term within 45 days) cannot be judged on the day someone starts. Lag Lens takes CSV rows of cohort members, each with an entry date, a lag allowance and an optional date the milestone was reached, and lets you scrub an observation date across the whole span. At every date it shows who is **eligible** to be judged (their window has closed), who was **observed** hitting the milestone within the lag, and who is still **immature** (window still open, or already hit but not yet mature).

The page has two panels:

1. **Data.** A textarea for CSV rows, a format guide, and three buttons: visualize pasted CSV, load a fictional demo, or reset.
2. **Scrub the observation date.** Milestone tabs (if the data has several), a date slider with step buttons and a date picker, five stat tiles, a plain-language insight line, a stacked stream of totals over every observation date, one animated ribbon per cohort, and a collapsible table view of the counts at the selected date.

## Privacy-safe inspiration

The idea comes from a familiar analytics trap: a retention or conversion chart that looks like it is falling off a cliff at the right edge, when in fact the newest cohorts simply have not had time to mature yet. Lag Lens makes that right-censoring visible instead of hiding it in a footnote.

No real data was used or needed. The bundled demo is an invented community pottery studio with ten weekly intakes, two milestones (`first_glaze` at 14 days and `returned_for_term_2` at 45 days), and numbers from a seeded pseudo-random generator. Every name, date and count is made up. The demo text itself begins with a comment line saying so.

## Opening

Open `index.html` directly in any modern browser. No server, build step, network access or install is required. Everything runs in the page; nothing is uploaded or stored, and Reset clears both the textarea and the chart.

Paste your own rows or press **Load fictional demo** to start.

### CSV format

```
cohort,entered,milestone,lag_days,reached,count
Spring,2026-03-02,first_return,14,2026-03-09,1
Spring,2026-03-02,first_return,14,,1
```

- `cohort` (required): group label.
- `entered` (required): start date, `YYYY-MM-DD`.
- `lag_days` (required): whole number of days allowed to reach the milestone.
- `reached` (optional): date the milestone happened; blank if not yet.
- `milestone` (optional): name; several names become tabs.
- `count` (optional): weight for grouped rows, default 1.

A header row is required, column order does not matter, and comma, tab or semicolon delimiters are detected automatically. Lines starting with `#` are comments. Bad rows are skipped and listed; the rest still draw. Soft limits guard against runaway input (50,000 rows, 150 cohorts, a span of roughly ten years).

### Rule applied at each observation date T

- Row is **not entered yet** while `T < entered`.
- Row is **immature** while `T < entered + lag_days`, split into "already hit" and "window open".
- Once mature, the row is **eligible**: **observed** if `reached` falls within the lag, otherwise "eligible, not observed".
- The **matured rate** is observed divided by eligible, so it never counts people who have not had their chance yet.

## Controls

| Control | Action |
| --- | --- |
| Observation date slider | Scrub T across the full span from first entry to the last date any window closes |
| −7d / −1d / +1d / +7d | Step T by days |
| ▶ Play / ❚❚ Pause | Animate T forward day by day; any manual change pauses |
| Date picker | Jump to an exact date |
| Milestone tabs | Switch milestone when the data has more than one |
| Stream chart | Hover for totals at a date; press or drag to scrub T directly |
| Cohort ribbon name | Tap, click or keyboard-focus a cohort for its breakdown at T; tap again or press Escape to close |
| Table view | Expand for the per-cohort counts at the selected date |

The stat tiles, insight line and a visually hidden live region update on every change, so screen readers hear the current counts. Reduced-motion preferences remove ribbon transitions and slow the optional autoplay.

## Why it was built

Most cohort tools either hide immature cohorts or quietly draw them as if they had failed. Both choices mislead. Making the observation date a first-class, scrubbable control turns "the data isn't ready yet" into something you can see move: ribbons fill in from the left as windows close, the matured rate stabilises, and the right-hand edge stays honestly grey until it has earned a colour.

## Format choice

- **Lane:** `data_visualization`
- **Mechanic:** CSV-to-observation-date scrubber with animated cohort ribbons. The user supplies rows, picks a date, and the whole picture re-derives from that date.

## Explicit bans avoided

This piece deliberately steers clear of the following formats:

- Guides, zines or atlases
- Branching stories
- Routing metaphors (maps, paths, journeys, pipelines)
- Launch simulators
- Scorecards or rubric meters
- Agent preflight checklists

It is a single interactive chart over user data, not narrative, not a grader, not a checklist.

## Files

- `index.html`: the complete, self-contained page (markup, styles and script).
- `README.md`: this file.

## Status

Independently reviewed and retested at a 390px viewport, including demo, date scrubbing, unusual CSV labels, and built-in model assertions. `READY` is written only after those checks.
