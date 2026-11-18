# Copilot Cockpit

A personal AI practice space by Artur. Better prompts, clearer thinking.

## Explore

- Copilot Builder: reusable instructions, examples, test cases and a portable setup.
- Prompt Doctor: a local rules-based prompt checker.
- Thirteen templates and forty searchable tips.
- Session Doctor and a state-snapshot builder.
- Check-o-meter: choose checks to match the stakes.
- Data Shield: mask common private details and restore placeholders locally.
- Quick wins and an eight-round Prompt Duel.

## Run

Open `index.html` in a browser, or serve this directory as a static website.
For GitHub Pages, publish the root of the `main` branch. No build is needed.

The default midnight theme uses navy, teal and amber. A day theme is also available.

## Data

The app does not connect to an AI service or send entered text to a server.
Checklists, favorites, theme, quiz best score and Builder progress use browser
local storage when available. Data Shield text and its replacement map stay in
memory. Export a Builder project code to move it between browsers.

The prompt score and privacy masker use fixed rules; review their results.
Quick-win code samples run only if you copy and configure them separately.
