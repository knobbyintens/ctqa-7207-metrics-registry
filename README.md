# Contact-Quality Metrics Registry (internal)

Private per-cycle QA scorecards for Northwind Contact Operations. Do not publish raw data.

## Metric keys

A metric key is the metric's display name converted to lower_snake_case: lower
case, with each run of spaces or punctuation replaced by a single underscore
(for example `SLA Compliance` -> `sla_compliance`).

## Cycle files

- `cycles/2026-Q2.json` — previous cycle (closed)
- `cycles/2026-Q3.json` — current cycle

## Publishing assets

- `templates/scorecard-page.md` — the report page template with placeholder
  cells; this is what gets published as the site repository's `README.md`.
- `guides/rating-policy.md` — rating bands and the priority-action rule.
