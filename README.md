# Homemade Detroit

> Real food from real neighbors — a home kitchen marketplace for Detroit.

Chefs post a rotating weekly menu (3–5 dishes, limited quantities) every Monday. Customers browse by zip code, pre-order by Wednesday, pick up Friday. Chefs keep 80% of every transaction.

## Phase 1 — Validate (Weeks 1–2)

Goal: 5 chef commits + 50 waitlist signups before writing a line of product code.

| Target | Goal |
|---|---|
| Chef commitments | 5 |
| Customer interviews | 20 |
| Waitlist signups | 50 |
| Compliance pathway | Known |

## Project structure

```
homemade-detroit/
├── site/                   # Waitlist landing page (Netlify)
│   └── index.html
├── docs/                   # Phase 1 research & planning
│   ├── phase1-tracker.xlsx       # Chef pipeline, interviews, waitlist, compliance
│   └── compliance-research.md   # Michigan cottage food law brief
├── README.md
└── netlify.toml
```

## Neighborhoods (Phase 1)

- Midtown
- Corktown
- Mexicantown
- East English Village
- Hamtramck

## Tech stack (Phase 2 — build)

- **Frontend:** Next.js
- **Database:** Supabase
- **Payments:** Stripe Connect
- **Media:** Cloudinary
- **Messaging:** Twilio

## Revenue model

- 20% transaction fee
- $9/mo Customer Insider tier (early access)
- $29/mo Chef Analytics tier
- Catering / Supper Club (Year 2)

## Live site

[homemade-detroit.netlify.app](https://homemade-detroit.netlify.app)
