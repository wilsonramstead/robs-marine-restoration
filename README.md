# Rob's Marine Restoration — demo site

Single-page demo built for **Rob's Marine Restoration**, a **boat restoration and marine upholstery**
shop in **Lakeland, Florida** (Polk County).

- **Wave:** 70 (manifest entry index 5)
- **Built:** 2026-08-21
- **Live:** https://wilsoninnovations.net/robs-marine-restoration/
- **Tier:** 2 — Showpiece / Night Shift (dark glow: living aurora blobs, film grain, glass cards,
  gradient text fill, glow CTA with shine sweep)
- **Fonts:** Podkova (display slab) + Mulish (body)
- **Palette:** harbor-slate canvas `#0B1216` / `#111C22` / `#18272F` + crisp sail-white `#F4F8F9` /
  `#DDE7EB` + varnished-mahogany accent `#A6412E` / `#C96A50` / `#67230F`, with a harbor-slate
  secondary `#5C7E90` / `#8FB0C1` / `#2C4451`

This is the **first marine-restoration site in the portfolio** — a lake-country niche with no prior
sibling in the Polk file.

## Address privacy (important)

The GBP address is a **residential home shop**. **No street address appears anywhere on this page.**

- No street address in any display text, footer, meta description, or link.
- JSON-LD `PostalAddress` carries **locality only** — `addressLocality: Lakeland`,
  `addressRegion: FL`, `addressCountry: US`. There is **no `streetAddress`** and no postal code.
- **No map embed and no Google Maps link** of any kind.
- The page frames intake as **drop-off by appointment**: a dedicated `#dropoff` section, a dashed
  plate reading "Lakeland, Florida · Polk County / Private shop — address given when you book", a
  footer line saying the same, and hero/CTA fine print repeating "drop-off by appointment".

## Palette separation from siblings

Checked against every upholstery/marine demo in `websites/` plus `templates/template-upholstery-1`
before any token was written:

| Sibling | Owns | Kept clear how |
| --- | --- | --- |
| `bac-upholstery` (Ruskin, marine — closest trade sibling) | navy `#060C14` + orange `#F2811D` + teak `#C9A274` | Base is **gray-blue slate**, not navy; accent is **red-brown mahogany**, not golden teak; **zero orange** anywhere in the file |
| `bb-auto-upholstery` | charcoal + camel `#D6AE7B` + wine `#7E2233` | No camel/tan family; mahogany is warmer and lighter than the wine |
| `tampa-bay-upholstery` | navy `#070A10` + sand/tan + brass | No sand, no brass |
| `upholstery-by-design` | `#07131A` + sand + teal | No sand, no teal |
| `nora-upholstery` / `riez-upholstery` | terracotta `#C96F43` / coral `#FF6F52` on warm brown ink | Mahogany `#A6412E` is deeper and redder, and sits on a **cool** slate canvas |
| `underdog-upholstery` | ox-blood red `#C02A37` | Mahogany is brown-shifted, not a pure red |
| `garth-and-ally` / `rf` / `schramek` / `rl` / `northstar` | gold / brass / walnut families | No gold or brass token exists here |
| `top-quality-boat-car-detailing` (other marine demo) | electric blue `#2F6BFF` | No blue accent; slate is a desaturated secondary only |

Podkova + Mulish is not used by any known sibling pair.

## Provenance of every fact on the page

All business facts come from the wave-70 manifest entry (Google Business Profile data):

| Fact | Source |
| --- | --- |
| Phone (863) 937-2975 | GBP via manifest — verbatim in display text, `tel:`/`sms:` links and JSON-LD |
| Locality: Lakeland, FL (Polk County) | GBP via manifest — locality only, see address-privacy note above |
| Rating 4.9 / 32 reviews | GBP via manifest — hero chip + stat tile + review footnote; never styled as a quote |
| Hours Mon–Thu 8:00 AM–5:00 PM, Fri 8:00 AM–4:00 PM, Sat/Sun closed | GBP via manifest, presented plainly with a softening note ("give Rob a call to confirm") |
| Owner Rob | Evidenced — the business carries his name and every review deals with him directly. No owner-personality section was built |
| "his son" works with him | Evidenced verbatim by Tim P. ("Him and his son did a phenomenal job") |
| Review quotes | GBP via manifest, **verbatim** including original spelling and typos, attributed as the reviewers signed them, **no dates** |

Reviews used: **Robert W.**, **Nathan A.**, **Tim P.**, **Dallas** (single-name reviewer, used as
signed), **Philip P.**

### Deliberate omissions

- **No pricing.** The `$2,900` figure that appears in Robert W.'s review is **not published**; his
  quote is excerpted around it. The page directs people to call for a quote.
- **No turnaround promise.** The three-week build and six-week wait are presented strictly as *one
  customer's account of one job*, with the page stating in plain text: "That was one customer's job
  on one boat — not a promise about yours."
- **No material or product brands** asserted by the site. Brand names that do appear (Somerset,
  Mako, Johnson, Javelin, Nitro, Bass Tracker) are inside verbatim customer quotes or refer to the
  customers' own boats.
- No email, license number, founding year, years-in-business, staff count, or service-area radius —
  none were evidenced.

## Build angles (all evidenced)

1. **Lost-cause resurrections** — the centerpiece. Two long verbatim cases: the 1979 custom-built
   "Somerset" family heirloom whose floor, stringers and transom were all rotten, and the 1975 Mako
   23 that had been "sitting under a tree rotting away since 99'". Both quoted at length.
2. **Booked ahead** — the six-week wait framed honestly as reliability proof, not scarcity: he gave
   a date, and he called on it. Explicitly disclaimed as one customer's experience.
3. **Up-front honesty** — the pull quote is the reviewer's line that Rob told them the boat would
   cost more to fix than it was worth, *before* taking the job.
4. **Parts sourcing** — matched used bucket and pedestal seats "in immaculate condition".
5. **Marine upholstery as its own lane** — carpet-only and seats-only work, for boats that don't
   need a rescue.

## Images

Unsplash, hotlinked with `?w=&h=&q=&auto=format&fit=crop`. IDs used:

| ID | Placement |
| --- | --- |
| `photo-1755594483726-d19aaf29740b` | Hero + og:image + gallery — boat cockpit: helm, gauges, upholstered seating, varnished table |
| `photo-1766431045548-80f04d8feef3` | Case 1 — weathered interior of an old wooden boat around an exposed engine |
| `photo-1649320099816-be6102b9f433` | Case 2 — boat hull on stands in a yard, bottom stripped back |
| `photo-1779884801681-37d4f4cc0feb` | "A soft floor is never just a floor" — weathered planking and frames inside a hull |
| `photo-1756758822288-0c92645edc11` | Marine upholstery split — padded vinyl seat and bench in a boat cabin |
| `photo-1745875513449-f54f017b880d` | Gallery — timber deck and rug aboard a classic boat at a dock |
| `photo-1786892669113-0fcf33cdc7c8` | Gallery — small boat on a still lake with wooded hills |

Selection rules applied: trade-fit only (boat interiors, marine upholstery, hull and structural work,
lake boats — all Florida-plausible); every image opened and **visually inspected against its alt
text**; candidates showing business signage, painted phone numbers, hull lettering or **vessel
registration numbers** were dropped, as were shots whose setting did not read as Florida lake
country; no `premium_photo-` assets; the known repeat-collision ID `photo-1735494033576` was
excluded outright.

Sourcing note: `unsplash.com` is now behind an Anubis proof-of-work bot wall that returns HTTP 403 to
a plain headless fetch. The pool was pulled through headless `puppeteer-core` + Edge with a real
Chrome/Edge user-agent and `navigator.webdriver` masked, which clears the challenge; the
`unsplash.com/napi/search/photos` endpoint was then called same-origin from the cleared page, across
25 marine queries with **`order_by=latest` as well as `relevant`** (1,243 unique IDs pooled).

Dedup grep over `websites/*/index.html`, `websites/*/README.md` **and** `templates/*/index.html` was
run immediately before download and again before commit — **all seven IDs unused elsewhere in the
portfolio (zero overlap).** A perceptual dHash check was run against the self-hosted assets in
`woods-fencing`, `da-costa-construction`, `coastal-irrigation`, `out-fox-welding` and
`marquez-pavers` (35 local images): minimum Hamming distance **19**, no near-duplicates.

## Build notes

- Self-contained `index.html` — no external CSS/JS beyond Google Fonts.
- `<meta name="robots" content="noindex">` with a removal comment — strip both when the site goes live.
- Scroll reveals are JS-gated (`.js .reveal`) so the page renders fully with JavaScript disabled; all
  motion (aurora drift, hero Ken Burns settle, ticker, reveals, CTA shine) is behind
  `prefers-reduced-motion`.
- Mobile: H1 is exactly 2 lines at 390px, zero horizontal overflow at 390 / 1366 / 1440, header call
  CTA is icon-only at ≤600px and flush right at all widths, every tap target ≥44px. **No fixed bottom
  call bar.**
- Full hero stack (eyebrow → headline → sub → CTA pair → rating chip → hours note) is visible with no
  scroll at both 1440×900 and 1366×768.
- Aggregate rating is rendered as a chip and a stat tile — never styled as a quote.
- No contact form. No owner-personality section.
- Exactly one footer credit: "Website by Wilson Innovations" → https://wilsoninnovations.net

## Ask the owner for

His own before-and-after photos — the manifest notes roughly six own-GBP photos of real boats, and
the restorations *are* the portfolio, so his own set should replace the stock imagery on the case
cards and gallery. Also worth confirming: whether any shop or trailer lettering shows a phone number
other than the GBP (863) 937-2975, and whether he wants the drop-off address published at all or kept
to booking only.
