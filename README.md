# PMO Toolkit

Free PMO utility suite — product roadmap decks, Gantt project plans, status reports and more. Questionnaire in, branded PowerPoint out.

## Try it

Live site: https://tilakboinapally.github.io/pmo-toolkit/ (once GitHub Pages is enabled)

Or open `index.html` in any browser — no install, no server, nothing is uploaded anywhere.

## Modules

- **Roadmap Deck (Module 1)** — pick a template (Timeline roadmap, Now / Next / Later, Executive), answer a short questionnaire (product, vision, audience, goal, headline metric), enter epics and features with owners, statuses and dates (or import both lists from CSV), let the draft assistant write the executive summary and speaker notes, run pre-flight checks, preview, and download a real 1–2 slide .pptx with your logo embedded.
- **Gantt Chart (Module 2)** — tasks and milestones with owners, dates, % complete, and finish-to-start dependencies drawn as arrows; computed critical path, today line, plan checks; seed tasks from your epics & features or import from CSV; download a branded Gantt .pptx slide.
- **Suite guide** — how the modules fit together and what's planned next.

Planned: Status Report Deck, RAID Log, Charter & Kickoff, Portfolio Dashboard.

## Shared spine

One project file (save/open as JSON) feeds every module: project dates, brand kit (logo, colors, footer), epics, features, tasks. Enter data once, reuse it in every deck. CSV import uses the same column conventions everywhere; downloadable templates are built into each module.

## AI draft assistant

Step 4 of the Roadmap Deck can call an LLM (Anthropic Muse or OpenAI GPT) with your own API key to draft the executive summary and speaker notes. The key is held in the browser tab only and never saved or sent anywhere except the provider you choose. Without a key, the built-in offline draft still works, and the exact prompt is always viewable and copyable.

## Privacy

The app runs entirely in your browser. No data is stored on any server; projects exist only as files you save (JSON) or decks you download (.pptx).

## How it's built

Single static page (`index.html`), PowerPoint export via PptxGenJS. No build step — edit the file, refresh, done.

## Contributing / feedback

Open an issue with what you tried and what happened.
