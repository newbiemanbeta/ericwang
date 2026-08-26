# ericwang

One-page personal site for Eric Wang — founder and growth operator.

**Status:** v1, awaiting Eric's review. Not yet on a custom domain.

---

## Stack

None. A single static `index.html` — no build step, no framework, no
dependencies, no backend. Fonts load from Google Fonts; everything else is
inline.

The page has no state, no users and no stored data, so there is nothing for a
database or a server runtime to do.

## Deploy

Vercel, Framework Preset **Other**, build and install commands left empty.
Pushes to `main` deploy automatically. Pushes to any other branch get their own
preview URL.

```bash
git add .
git commit -m "your message"
git push
```

## Design

- Near-black `#0B0C0E`, cool grey secondary `#767C86`, one accent: cobalt `#4D6BFF`
- Two typefaces — Helvetica Neue (falling back to Inter Tight off macOS) for
  everything typographic, JetBrains Mono for section eyebrows and stat labels
- Seven numbered sections, one CTA, no navigation
- Structure follows austinlee.io; palette and type follow Eric's stated
  direction (dark, cool, minimal, Helvetica Neue Bold)

## Known open items

- Domain not purchased. Contact points at `ericwangbusiness@gmail.com`.
- No Calendly yet — the "Book a call" button is a `mailto:` with a prefilled
  subject. Swap the `href` when a booking link exists.
- Stat bar fill percentages are a visual device, not data.
- Blankethoodies has no outbound link; its store is offline.
- Four brand cards have no link — no web presence found for Based Bodyworks,
  Phoilex, or Crafted by Kaiyo.
- Fourth stat is `$0 outside capital raised`. If Eric confirms a count of
  brands founded, there is a marked swap point in `index.html`.

## Route comparison

Built as one of two routes put to Eric, the other being the same page generated
in Base44. Base44 produces a React/Vite frontend with Node functions and a
managed Postgres instance; this route produces one file. Same content, same
spec, both live — the comparison is the tool and the process, not the copy.
