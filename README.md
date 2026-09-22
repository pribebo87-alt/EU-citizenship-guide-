# Every Door in Europe

A guide to every citizenship pathway across 46 European countries — by descent, marriage, naturalisation, and investment — with current costs, dual-citizenship rules, and the countries that are effectively closed to outsiders.

**Live app:** `index.html` (once GitHub Pages is turned on, this becomes your live site — see setup steps below)

## What's in this repo

| File | Purpose |
|---|---|
| `index.html` | The app itself — this is what GitHub Pages serves as your homepage |
| `privacy-policy.html` | Required for Play Store submission and Stripe/AdSense approval |
| `icon-512.svg` | Main app icon |
| `icon-maskable-512.svg` | Android adaptive icon (safe-zone padded) |

## Features

- 46 countries covering descent, marriage, naturalisation, and investment routes
- English / Hindi language toggle
- Compare & Shortlist quiz — ranks countries by your budget, timeline, ancestry, and dual-citizenship needs
- Step-by-step application checklists (paywalled: $3 for any 4 countries, $5/month for all)
- Ads shown to free/pack users, hidden for All-Access subscribers
- "Recently changed" tracker for major 2024–2026 rule changes (Malta, Spain, Germany, Italy, Latvia)

## Setup

Full step-by-step instructions (free hosting, Android packaging, Play Store submission) are in `GITHUB_PAGES_SETUP.md` in this project's original chat — see also `PLAY_STORE_LISTING.md` for ready-to-paste store listing text, and `LAUNCH_CHECKLIST.md` for the complete launch plan.

**Quick start:**
1. Turn on GitHub Pages: Settings → Pages → Source: `main` branch, `/ (root)` folder
2. Your site goes live at `https://YOUR-USERNAME.github.io/REPO-NAME/`
3. Fill in the `[FIELDS]` in `privacy-policy.html` with your real app name and support email

## Monetization (not yet wired — safe placeholders in place)

- **Payments:** Stripe Checkout integration is written but inactive (`STRIPE_CHECKOUT_ENDPOINT = null` in `index.html`). Needs a Stripe account + a deployed backend function to activate.
- **Ads:** Google AdSense integration is written but inactive (`AD_CLIENT_ID = null` in `index.html`). Needs AdSense approval to activate.

Both show clearly-labelled demo placeholders until configured — the app is fully usable without either.

## Disclaimer

This app provides general informational content compiled from public national-authority sources. It is not legal advice. Confirm current rules with the relevant country's immigration authority or a licensed immigration lawyer before making decisions.
