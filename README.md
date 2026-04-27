<div align="center">

# 💸 awesome-free-stack

**10 open-source repos that replace $415,000/year in enterprise software**

[![Stars](https://img.shields.io/github/stars/seelffff/awesome-free-stack?style=flat-square&color=5b5bd6)](https://github.com/seelffff/awesome-free-stack)
[![Updated](https://img.shields.io/badge/updated-april%202026-4ade80?style=flat-square)](https://github.com/seelffff/awesome-free-stack)
[![Twitter](https://img.shields.io/badge/twitter-@seelffff-1d9bf0?style=flat-square&logo=x)](https://x.com/seelffff)

</div>

---

## 💰 before vs after

| | annual cost |
|---|---|
| enterprise stack (Zapier + Tableau + Intercom + Slack + ...) | **$415,000/year** |
| everything below | **$0** |

---

## 📦 the repos

### 1. [supabase/supabase](https://github.com/supabase/supabase) — ⭐ 73K+

**replaces:** Firebase + Auth0 — `$15,000/year`

Supabase is the open-source Firebase alternative — but built on Postgres instead of a proprietary NoSQL database. You get a full backend out of the box: relational database with real-time subscriptions, built-in authentication (email, OAuth, magic links, phone), file storage with CDN, auto-generated REST and GraphQL APIs, and edge functions for serverless logic.

The difference from Firebase: your data lives in a standard Postgres database you fully control. No vendor lock-in, no proprietary query language, no surprise billing. You can self-host on any VPS or use the cloud version with a generous free tier. Auth0 alone costs $23K+/year for 50K users — Supabase includes auth for free.

---

### 2. [n8n-io/n8n](https://github.com/n8n-io/n8n) — ⭐ 47K+

**replaces:** Zapier Enterprise — `$50,000/year`

n8n is a self-hosted workflow automation platform with a visual node editor and 400+ built-in integrations. Connect any app to any app, trigger automations on schedules or webhooks, transform data between steps, and run custom JavaScript or Python when the built-in nodes aren't enough.

What makes it different from Zapier: you run it on your own server, so there are no per-task fees, no data leaving your infrastructure, and no artificial limits on workflow runs. Zapier Enterprise charges per task — at any meaningful scale that adds up to $50K+/year fast. n8n is a one-time server cost. The visual editor is just as good, and for developers the code nodes make it significantly more powerful.

---

### 3. [metabase/metabase](https://github.com/metabase/metabase) — ⭐ 38K+

**replaces:** Tableau / Looker — `$70,000/year`

Metabase is an open-source business intelligence tool that lets anyone on your team ask questions about your data without knowing SQL. Connect it to Postgres, MySQL, MongoDB, Snowflake, BigQuery, or 20+ other sources, then build charts, dashboards, and automated reports in minutes.

Tableau licenses start at $70/user/month — for a 50-person company that's $42K/year just for the tool, before training or implementation costs. Looker (Google) starts at $100K/year for enterprise. Metabase self-hosted is completely free. The cloud version starts at $500/month but the open-source version covers 95% of real-world use cases. Non-technical stakeholders can actually use it without support from engineering.

---

### 4. [calcom/cal.com](https://github.com/calcom/cal.com) — ⭐ 31K+

**replaces:** Calendly Enterprise — `$20,000/year`

Cal.com is the open-source Calendly — fully self-hostable, white-labelable, and infinitely customizable. It handles everything: one-on-one bookings, round-robin team scheduling, collective events, recurring meetings, custom availability rules, buffer times, and payment collection via Stripe.

Calendly Enterprise costs $16/user/month minimum, and at the enterprise tier with SSO, Salesforce integration, and admin controls you're looking at $20K+/year for a mid-size team. Cal.com gives you all of that plus full source code access, your own branding, and the ability to embed it anywhere. Integrates with Google Calendar, Outlook, iCal, Zoom, Google Meet, and 30+ other tools.

---

### 5. [OpenBB-finance/OpenBB](https://github.com/OpenBB-finance/OpenBB) — ⭐ 34K+

**replaces:** Bloomberg Terminal — `$30,000/year`

OpenBB is the open-source investment research platform — a direct alternative to the Bloomberg Terminal at $24K+/year per seat. It aggregates financial data from 100+ providers: equities, options, crypto, forex, macro economics, alternative data, and earnings. All in one interface with a built-in Python SDK.

The terminal has a CLI interface plus a web dashboard, and the SDK lets you pull any data programmatically into your own models and scripts. For quants, analysts, and anyone doing systematic research, this replaces a Bloomberg subscription entirely for most workflows. You can extend it with custom data sources and build on top of it — something you simply can't do with Bloomberg.

---

### 6. [mattermost/mattermost](https://github.com/mattermost/mattermost) — ⭐ 30K+

**replaces:** Slack Enterprise — `$15,000/year`

Mattermost is a self-hosted team messaging platform that replicates everything Slack does — channels, threads, direct messages, voice calls, file sharing, integrations, bots — but runs entirely on your infrastructure. Your messages never touch a third-party server.

Slack Pro is $7.25/user/month, Slack Business+ is $12.50/user/month, and Slack Enterprise Grid is negotiated but typically $15-25/user/month. For a 50-person team that's $7,500-$15,000/year minimum. Mattermost self-hosted is free for unlimited users and unlimited message history. The compliance and data sovereignty features that cost extra in Slack come built-in — critical for healthcare, finance, and government use cases.

---

### 7. [PostHog/posthog](https://github.com/PostHog/posthog) — ⭐ 22K+

**replaces:** Amplitude + Mixpanel — `$25,000/year`

PostHog is an all-in-one open-source product analytics platform. Instead of paying for five separate tools, you get everything in one: event tracking, user identification, funnels, retention analysis, session recording and replay, heatmaps, feature flags, A/B testing, surveys, and a data warehouse connector.

Amplitude's Growth plan starts at $995/month. Mixpanel's Growth plan adds another $500+/month. Together for a mid-size product team you're at $17K-25K/year before you even add session replay (FullStory at $450/month) or feature flags (LaunchDarkly at $300/month). PostHog self-hosted covers all of it for free. The events-based pricing on the cloud version is generous — most companies never pay anything meaningful.

---

### 8. [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) — ⭐ 22K+

**replaces:** Intercom — `$40,000/year`

Chatwoot is an open-source customer support platform with a true omnichannel inbox. Handle conversations from email, live chat, WhatsApp, Telegram, Twitter/X, Facebook Messenger, Instagram, and phone — all in one interface. Includes a CRM, canned responses, labels, teams, CSAT surveys, and a basic AI assistant.

Intercom's pricing starts at $74/seat/month and scales aggressively — a team of 10 support agents with Fin AI and phone support easily exceeds $3,500/month ($42K/year). Chatwoot self-hosted is completely free, handles unlimited agents and inboxes, and the API lets you build any custom automation on top of it. The UI is clean and modern — agents actually like using it.

---

### 9. [plausible/analytics](https://github.com/plausible/analytics) — ⭐ 20K+

**replaces:** Google Analytics 360 — `$150,000/year`

Plausible is a privacy-first, lightweight web analytics tool that gives you the metrics that actually matter — pageviews, unique visitors, bounce rate, top sources, top pages, countries, devices — without the GDPR nightmare, cookie banners, or data collection that makes legal teams nervous.

Google Analytics 360 (the paid enterprise version) starts at $150,000/year. But even if you use the free GA4, you're feeding all your user behavior data to Google. Plausible's script is 45x smaller than GA (< 1KB), it doesn't use cookies, it's fully GDPR/CCPA compliant out of the box, and you can self-host it so the data never leaves your servers. Simple dashboard that actually loads fast. No sampling, no complex funnels you need a data analyst to interpret.

---

### 10. [Kreo](https://t.me/KreoPolyBot?start=ref-kreohub) — wallet tracking + copy trading

**replaces:** manual Polymarket research — hours/day

Kreo tracks the top-performing wallets on Polymarket in real time and automatically copies their trades to your account. No code required, no manual monitoring, runs 24/7.

The top Polymarket traders use sophisticated models to find mispriced markets — they're not betting randomly. Kreo lets you follow those wallets without building the infrastructure yourself. Set your position sizes, connect your wallet, and let it run while you focus on everything else.

---

## 📊 savings breakdown

| repo | replaces | saved/year |
|------|----------|------------|
| supabase | Firebase + Auth0 | $15,000 |
| n8n | Zapier Enterprise | $50,000 |
| metabase | Tableau / Looker | $70,000 |
| cal.com | Calendly Enterprise | $20,000 |
| OpenBB | Bloomberg Terminal | $30,000 |
| mattermost | Slack Enterprise | $15,000 |
| posthog | Amplitude + Mixpanel | $25,000 |
| chatwoot | Intercom | $40,000 |
| plausible | Google Analytics 360 | $150,000 |
| **total** | | **$415,000/year** |

---

<div align="center">

found this useful? **star the repo** and follow [@seelffff](https://x.com/seelffff) for more

</div>
