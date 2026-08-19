# ETH Zürich × Takeuchi Lab — Research Exchange Visit (Sept 7–11, 2026)

Schedule site for the pre-symposium exploratory visit by three guests from the
Soft Robotics Laboratory, ETH Zürich, ahead of BRS 2026 (Sept 16–18, Tokyo).

**Live page:** https://<YOUR-GITHUB-USERNAME>.github.io/<REPO-NAME>/

## Files

| File | Purpose |
|---|---|
| `index.html` | The schedule site. Fully self-contained — all CSS, JS and logos are embedded, so it works offline and needs no build step. |
| `ETH_visit_schedule_content.xlsx` | Source of truth for the content. Edit the `Schedule` tab; see the `Instructions` tab for the column rules. |

## How to update

1. Edit `ETH_visit_schedule_content.xlsx` (the `Schedule` tab).
2. Regenerate `index.html` from it.
3. Commit and push — GitHub Pages redeploys automatically within a minute or so.

```bash
git add -A
git commit -m "Update schedule"
git push
```

## Legend

- **ALL 3** (tri-colour stripe) — all three ETH guests attend together
- **ASIA / PABLO / MANUEL** — that guest only
- **TBD** (red) — host or detail not assigned yet

Affiliation tags: **TLab** Takeuchi Lab · **IIS** Institute of Industrial Science · **ETH** ETH Zürich.
