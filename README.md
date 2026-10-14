# Factor · Market Intelligence

Public briefing site for Factor shareholders: factoring, invoice discounting and UAE healthcare-receivables news, insurer watchlist, rates, regulation and competitors.

- `index.html` — the page (static, no build step).
- `data/*.json` — the content. A scheduled Claude task refreshes these files every morning (Dubai time) and commits them here; GitHub Pages republishes automatically.
- `data/meta.json` — time of the last refresh, shown in the page footer.

To change the design, edit `index.html`. To correct a story or figure, edit the matching file in `data/`.
