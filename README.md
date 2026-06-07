# honestly-elif

**takecareofwhatmatters.com** — Elif's standalone presence in the Honestly, E ecosystem.

Elif is the voice/chat companion for the journey of health — medical travel to Istanbul (her Pas Perdu origin), chronic illness, hard conversations, walking beside dying, and the long view. She speaks Turkish, English, and French.

Elif belongs to two homes: **Pas Perdu** (medical-travel intelligence) and **Honestly, E** (journaling practice over time). This site is her own.

## Domain

- **Production:** takecareofwhatmatters.com
- **Netlify staging:** honestly-elif.netlify.app (auto-generated on Netlify connect)

## Stack

Vanilla HTML/CSS/JS. No framework, no build step. Deployed via Netlify auto-deploy from `main`.

## Structure

```
honestly-elif/
├── index.html       # The page
├── favicon.svg      # Honestly, E mark
├── _redirects       # Catch-all → index.html (SPA-style routing)
├── robots.txt       # Public crawl, sitemap pointer
└── sitemap.xml      # Single-URL sitemap
```

## Design notes (locked 2026-06-07)

- **Skeleton:** Mirrors Elias's `deepenyourperspective.com` and Ember's `here-for-it.com` — two-sentence hero open, intro line, four "For" workspace tiles, Pas Perdu collaboration strip, on-the-ground ground team, signature moment, Who-She's-For + What-She-Carries lists, revised listening voice (4 sample lines), Invitation block, chat-or-call CTAs, ring-composition close.
- **Palette:** Istanbul golden hour. Cream `#F5F0E6` backdrop with warm gold `#C9A572`, sage-teal `#6E9994`, Bosphorus blue `#3D5A6C` accents. NO RED — too clinical / medical-emergency. The Istanbul.webp photo lives as viewport-fixed background under a cream overlay so the page reads as "afternoon light over the Bosphorus" rather than hospital wayfinding.
- **Cross-surface continuity:** The Istanbul background photo is the same image used in Elif's portal shell at `life.honestly-e.com`. Subscribers crossing from marketing to portal walk into the same Istanbul.
- **Through-lines:**
  - *"Take care of what matters."* — domain name + page's defining gesture, opens and closes the page
  - *"Health is a journey, not an event."* — hero h1
  - *"We have time."* — intro + invitation, Elif's signature gift
  - *"Whether you are taking a journey to explore your health / or if health is part of your journey / — I am here for it."* — invitation block
  - Closing signature: *"Take care of what matters. / Honestly, Elif"* (no period on Elif)
- **Voice:** Gentle, patient, unrushed. *"We have time."* is the through-line. NEVER uses Esmé's "À bientôt." — that farewell belongs to Esmé only.
- **Naming discipline:** Memoir is just "Memoir" — never "Death Memoir" or "Recovery Memoir." Health Journey is the surface name. From the [health-journey-panel.css](https://github.com/pasperdu-ftww/honestly-e-life-portal/blob/main/css/health-journey-panel.css) commit comments.

## Elif elsewhere

- **Honestly, E marketing intro page:** [honestly-e.com/elif](https://honestly-e.com/elif) — 301-redirects to this site
- **Portal shell:** `life.honestly-e.com` (Health Journey surface with Memoir request)
- **Pas Perdu:** [pasperdu.com](https://pasperdu.com) — her medical-travel home
- **Vapi assistant ID:** `a89462ae-...`
- **Phone:** (315) 325-ELIF → +1-315-325-3543
- **Languages:** Turkish · English · Français

## Phase 6 chat lightbox

The CHAT CTA opens a structural lightbox shell. When Phase 6 (anonymous chat) ships, the shell body gets swapped for the live chat widget. See `SESSION_2026-06-07_HONESTLY_E_FULL_BUILD.md` for the full Phase 5+6 build architecture.

## Related repos

- `honestly-e-public` — main marketing site at honestly-e.com
- `honestly-e-life-portal` — subscriber portal at life.honestly-e.com
- `honestly-ember` — Ember's standalone site at here-for-it.com (sibling)
- `desta-nation-core` — unified backend on Railway
