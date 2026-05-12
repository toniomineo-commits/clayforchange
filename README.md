# Clay for Change

Single-page static site for Antonio &amp; Josef's wedding (2026-06-20).

Guests pick one of 10 handmade ceramic vases, choose a charity, set a donation
amount, and reserve their vase. Reservations are shared across all devices via
Supabase; email notifications go out via EmailJS.

## What's here

- `index.html` — the entire site. No build step, no framework.
  - Talks to the same Supabase backend (`moptegvrlzemfurcciaa`) as the wedding
    site at `thebub.us/clay-for-change`, so vase availability is automatically
    synced between the two domains.
  - EmailJS sends reservation alerts to `toniomineo@gmail.com`.

## Deploy

Vercel auto-deploys from `main` on push. Domain: `clayforchange.org`.

## Future

After the wedding this page becomes the founding-moment case study for a
broader "Clay for Change" platform — pop-up events at ceramic studios, an
online shop of donated pieces, and a charity-gifting flow.
