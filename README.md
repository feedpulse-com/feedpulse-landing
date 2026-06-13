# feedpulse-landing

> Mini product tour and install snippets for **[FeedPulse](https://feed-pulse.com)** — 17 free embeddable widgets and 12 free SEO checkers. No signup, no paid tier.

This repo is a quick tour through the **5 most-searched FeedPulse widgets**, each with a one-line install snippet you can paste into any HTML, WordPress, Shopify, Webflow, Ghost, or Substack site. Every widget below is free forever.

The dev-audience widgets (live visitor feed, GitHub stars, npm downloads, Discord members) each have their own example repo in this org — see [the section near the bottom](#also-in-this-org--dev-focused-example-repos).

---

## What is FeedPulse?

FeedPulse is a free SEO + web-analytics toolkit aimed at indie developers, bootstrapped SaaS founders, content creators, and small businesses who need real data without committing to a $99/mo subscription.

- **19 embeddable widgets** — live traffic feed, flag counter, online visitors, GitHub stars, npm downloads, Discord members, weather, crypto/stock tickers, countdown, clicks heatmap, comments, YouTube/Twitch live, page-speed badge, SEO trust badge, visitor globe, AI site chat, and more.
- **10 SEO checkers** — Traffic Rank (Tranco), Domain Authority (Moz), Domain Rating (OpenPageRank), Backlinks, SERP position, Index check, Lighthouse / Web Vitals, Page Speed (Google PSI), Trust Score, Domain Age.
- **Transparent data sources** — every metric's upstream provider is publicly listed at [feed-pulse.com/data-sources](https://feed-pulse.com/data-sources).

Every tool is free forever. There is no premium plan, no email gate, no upsell. Funded by an inline "powered by FeedPulse" link inside each widget — the same model that ran [Flag Counter](https://flagcounter.com), [classic StatCounter](https://statcounter.com), and the original [Feedjit](https://web.archive.org/web/2010*/feedjit.com).

---

## Top 5 widgets — install snippets

> Every snippet is a single `<script async>` tag. Drop it in your site's `<head>` (theme header, Webflow Embed component, Ghost code injection, Shopify theme.liquid, or plain `index.html`). No build step. No plugin.

### 1. Weather widget

Live forecast for any city in the world. Pick units (°C / °F), theme (light, dark, obsidian, mint, sand), and language (12 supported). Powered by Open-Meteo's free public API — no key, no signup.

```html
<!-- Copy your personalized snippet from https://feed-pulse.com/free-weather-widget -->
<script async src="https://feed-pulse.com/api/embed/weather?lat=51.51&lon=-0.13&place=london"></script>
```

[Customize city + theme → feed-pulse.com/free-weather-widget](https://feed-pulse.com/free-weather-widget)

---

### 2. Countdown widget

A live countdown timer for any future date — product launches, sale endings, event start times. Auto-refreshes per second, renders as a card or inline pill.

```html
<!-- Copy your personalized snippet from https://feed-pulse.com/free-countdown-widget -->
<script async src="https://feed-pulse.com/api/embed/countdown?to=2026-12-31T23:59:59Z"></script>
```

[Set your target date → feed-pulse.com/free-countdown-widget](https://feed-pulse.com/free-countdown-widget)

---

### 3. Clicks heatmap

A site-wide click heatmap recorder. Paste once in `<head>`, see aggregated click patterns rendered as an overlay on a fresh screenshot of each page. Privacy-by-default: clicks bucketed by 10-pixel cells so individual visitors stay anonymous.

```html
<!-- Copy your personalized snippet from https://feed-pulse.com/heatmap -->
<script async src="https://feed-pulse.com/api/embed/clicks_heatmap?site_id=YOUR_SITE_ID"></script>
```

[See your heatmap → feed-pulse.com/heatmap](https://feed-pulse.com/heatmap)

---

### 4. Flag counter

The classic "country flags of recent visitors" widget — same tradition as flagcounter.com, but Lighthouse-100 fast and cookie-free.

```html
<!-- Copy your personalized snippet from https://feed-pulse.com/free-flag-counter-widget -->
<script async src="https://feed-pulse.com/api/embed/flag_counter?site_id=YOUR_SITE_ID"></script>
```

[Customize layout + colors → feed-pulse.com/free-flag-counter-widget](https://feed-pulse.com/free-flag-counter-widget)

---

### 5. Live traffic feed

Last 10 visitors to your site in a scrolling real-time feed — country, city, referrer, time-ago. Auto-refreshes every 3 seconds. See [`traffic-feed-example`](https://github.com/feedpulse-com/traffic-feed-example) in this org for full docs.

```html
<!-- Copy your personalized snippet from https://feed-pulse.com/free-live-traffic-widget -->
<script async src="https://feed-pulse.com/api/embed/traffic_feed?site_id=YOUR_SITE_ID"></script>
```

[Customize → feed-pulse.com/free-live-traffic-widget](https://feed-pulse.com/free-live-traffic-widget)

---

## Also in this org — dev-focused example repos

The 4 widgets dev portfolios + open-source project sites love. Each has its own repo with full docs:

- [`traffic-feed-example`](https://github.com/feedpulse-com/traffic-feed-example) — live visitor feed
- [`github-stars-example`](https://github.com/feedpulse-com/github-stars-example) — ⭐ count badge for any repo
- [`npm-downloads-example`](https://github.com/feedpulse-com/npm-downloads-example) — weekly/monthly downloads badge
- [`discord-members-example`](https://github.com/feedpulse-com/discord-members-example) — live Discord member counter

---

## Where to find the other 14 widgets

| Surface | What it does |
|---|---|
| [Widget gallery](https://feed-pulse.com/widgets) | Interactive previews + customizer for all 19 widgets |
| [Free SEO tools](https://feed-pulse.com/tools) | 10 free SEO checkers (DA, DR, backlinks, SERP, Lighthouse, page speed, trust score, domain age, index check, traffic rank) |
| [Data sources](https://feed-pulse.com/data-sources) | Public list of every upstream provider + refresh cadence |
| [Explore](https://feed-pulse.com/explore) | Directory of public FeedPulse dashboards |

---

## License

[MIT](LICENSE) — fork it, paste it, modify it.

## Found a bug? Got feedback?

Open an [issue](https://github.com/feedpulse-com/feedpulse-landing/issues) or reach out at [feed-pulse.com](https://feed-pulse.com).
