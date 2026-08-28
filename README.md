# Work Log & Activity Calendar

A single-file daily work tracker for teaching, research, training, and professional development.

## Use it

Open `index.html` in a browser, or publish it with GitHub Pages:
**Settings → Pages → Source: Deploy from a branch → `main` / `root`.**
The app then lives at `https://<username>.github.io/<repo>/`.

No build step, no dependencies, no server. Everything is one file.

## How it works

- **Commitments** — the things you spend time on, in four categories: Courses, Research projects, Training projects, Professional development. Each can carry a weekly schedule (e.g. Wed 10:30–12:00).
- **Calendar** — Month and Week views show scheduled blocks as dashed outlines and logged work as solid ones. A thin coloured bar under each date shows how that day's hours split across the four categories.
- **Day page** — click any date. Tick off what was scheduled, add entries with times or just hours, and write the day's reflection.
- **Review** — hours by category and by commitment over a week, month, 90 days, or all time, plus your recent reflections.

## Keyboard

`1`–`4` switch views · `←` `→` move through time · `n` new entry · `t` jump to today

## Data

Stored in your browser. **Back up JSON** downloads everything; **Restore** reads it back — that's how you move between machines or browsers. **Export CSV** produces a flat table (one row per entry, plus reflections) for reporting, Excel, or R.

Starter commitments are included as examples. Edit or archive them from the sidebar; archiving keeps past entries intact.
