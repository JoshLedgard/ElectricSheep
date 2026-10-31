# Cohort Mixer

Daily Surprise · October 31, 2026

## What it is
An offline, hands-on subscription cohort model. Eight fictional monthly cohorts join over a twelve-month horizon. Edit how many subscribers join each month, their price, and the share of each cohort that remains subscribed each month. The active-subscriber chart and month-12 revenue readout update as you change assumptions. Download a CSV of the entire synthetic model.

This is an illustrative model, not a forecast: it assumes an identical acquisition count for the first eight months, one fixed price, no new subscribers in months nine through twelve, and no reactivation, upsells, or costs. Each retention percentage is relative to the original cohort size, not the prior month.

## Privacy-safe inspiration
Inspired by the general pleasure of turning product assumptions into something tactile. The starting values are invented; there is no personal or business data in the page.

## How to open
Open `index.html` in a current browser, including from `file://` while offline. There is no install, server, account, analytics, or network dependency. Edits remain in the current tab; download CSV before closing if you want to keep them.

## Controls
Change **New subscribers each month** or **Monthly price** for immediate recalculation. The **Monthly survival** field is used when you press **Reset to assumptions**, which asks for confirmation before discarding edited cells. Scroll the cohort table horizontally on a narrow phone. Tap a colored percentage cell to select it, then use the numeric **Selected retention** field or the ±5-point buttons. The joining-month cell remains 100% and cannot be edited. To prevent impossible reactivation, edits cannot exceed the prior month's retention and will cap any later values above the new value. Blank cells represent months before a cohort joined and cannot be edited. On a narrow phone, scroll the chart horizontally for readable axes. **Download CSV** exports months 1–12 with active subscribers, revenue, acquisition, and each cohort's retention percentage. Keyboard users can Tab to cells and input fields; the table is also a focusable scroll region.

## Why it was built
Retention and acquisition are easy to talk about abstractly. Painting one cohort's actual trajectory makes their compounding effect visible without asking for any real data.

## Format choice
- **Lane:** `startup_growth_experiment`
- **Mechanic:** select and numerically repaint fictional cohort retention cells, then inspect recomputed subscriber/revenue curves and export the model.

## Explicit bans avoided
Not a field guide, atlas, almanac, codex, zine, choose-your-own or branching story, signal/cartographer/constellation/routing puzzle, launch or readiness simulator, scorecard or rubric meter, abstract agent preflight, or generic generator. Unlike the preceding audio cutter, teleprompter, and execution timeline, this is an editable subscription-cohort model.
