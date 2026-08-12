# fahadmuhammad.com

Static site. Deploys to GitHub Pages from the repository root.

## Files

| File | Purpose |
|---|---|
| `index.html` | Entire site — HTML, CSS and JS in one file, no build step |
| `CNAME` | Custom domain (`fahadmuhammad.com`) |
| `robots.txt` | Crawl directives + sitemap pointer |
| `sitemap.xml` | Single-page sitemap — update `lastmod` when you edit content |
| `assets/fahad-portrait.jpg` | Hero portrait, 700×700 |
| `assets/og-image.jpg` | Social preview card, 1200×630 |
| `assets/twitter-card.jpg` | Social preview, 600×315 |
| `assets/fahad-avatar.jpg` | Apple touch icon, 320×320 |
| `assets/favicon.svg` | Favicon |

## Deploying

Replace the contents of the repo root with these files, commit, push. GitHub Pages
serves it directly — no build, no dependencies.

After deploying, submit `https://fahadmuhammad.com/sitemap.xml` in Google Search
Console so the new structured data gets picked up.

## Updating the numbers

Citation count (`222`) and publication count (`17`) appear in the hero stat block,
the Evidence index row for scholarly articles, the Publications section intro, the
meta description, the og:description, the twitter:description, the Contact profile
list, and the generated `assets/og-image.jpg`. Update them together.

All 17 publications are now listed in full, grouped as: Under review (3, TRB 2027),
Conference proceedings (4), Journal articles (10). Per-paper citation counts come
from Google Scholar.

### Publication counts

The mis-attributed plant-biology paper has been removed from Google Scholar, so
Scholar and this site now agree: 17 publications, 222 citations, h-index 8,
i10-index 8.

## Proposals section

`#proposals` lives at the end of the Roles section. Six proposals, three columns
(Proposal / Program / Focus) — no status column. The WisDOT row carries `class="win"`
for the blue highlight because it is the funded one; the intro paragraph above the
table is what states that. Move `class="win"` if another proposal gets funded.

NVIDIA is named in the sponsor column. This is the only company named on the site,
and it appears as a factual proposal sponsor rather than as a target employer.

## Research programs

Six cards in `#research`: CrossTraj, roadside perception evaluation framework,
CrossRisk, USDOT TRAVELS rural autonomy, GLANCE (nighttime glare dataset), and
human-executable connected-vehicle speed advisories.

GLANCE and CrossTraj are both declared as schema.org `Dataset` entities in the
JSON-LD block, which is what makes them eligible for Google Dataset Search. Once
either is publicly released, add a `distribution` and `url` field to its entity.

The speed advisory project is tagged "In progress". Update the card and add a tag
when results exist.

## Still to confirm

1. **NSF I-Corps** — written as I-Corps (Milwaukee I-Corps program, five workshops).
2. **Tsinghua master's dates** — omitted on the site because the LinkedIn dates
   conflict with the listed engineering roles. Fix on LinkedIn, then add here.
3. **Peer review** — currently generic. Add specific journal / conference names.
4. **IEEE membership grade** — Member, Senior Member, Student Member.
5. **h-index / i10-index** — omitted pending current Google Scholar figures.
6. **WisDOT award amount** — shown as ~$125K, sourced from the Digital Journal interview.
