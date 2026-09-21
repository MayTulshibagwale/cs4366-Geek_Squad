# cs4366-Geek_Squad

CS4366 Senior Capstone Fall 2026: Geek Squad team webpage.

## Live site

https://maytulshibagwale.github.io/cs4366-Geek_Squad/

## Getting started

The site is a single static page (`index.html`). There is nothing to install and no build step.

1. Clone the repo:

   ```bash
   git clone https://github.com/MayTulshibagwale/cs4366-Geek_Squad.git
   cd cs4366-Geek_Squad
   ```

2. Run it locally:

   ```bash
   python3 -m http.server 8000
   ```

   Then open http://localhost:8000. Opening `index.html` directly also works, but the page
   cannot load `data.json` from a `file://` address, so use the local server to see saved content.

## Editing the page

1. Open the site and click **Edit page**.
2. Change the team, meetings, or schedule tables, then click **Save to site**.

Saving commits a `data.json` file to this repo through the GitHub API, so it needs a GitHub
access token with **Contents: Read and write** on this repository. Only people with write
access to the repo can save. The token is pasted once and stays in your browser only. Never
commit it or share it.

Until the first save, the page shows its built-in defaults.

## Project layout

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: markup, styles, and scripts |
| `data.json` | Team, meetings, and schedule data (created on the first save) |
| `README.md` | This file |

## Deploying

The site is served by GitHub Pages from the `main` branch at `/`. Pushing to `main`
redeploys it, usually within a minute.

## Team

TODO: add team members, roles, and course details.
