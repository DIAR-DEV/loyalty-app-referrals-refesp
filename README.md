# loyalty-app-referrals-refesp

Referral landing page for Refaccionaria Espinoza's loyalty app (flavor/env code: `refEsp`), based on [loyalty-app-referrals](https://github.com/canamend/loyalty-app-referrals).

Plain static HTML/CSS/JS — no build step. The page served to end users lives at `docs/index.html` (intended for GitHub Pages from the `/docs` folder).

## Placeholders

`docs/index.html` currently uses `{{REFESP_*}}` placeholders in place of real branding/copy/config. See the asset spec shared separately for what's needed and in what format, and replace each placeholder before deploying.

## Local preview

Open `docs/index.html` directly in a browser, or serve the repo root with any static file server and visit `/docs/?ref=test123`.
