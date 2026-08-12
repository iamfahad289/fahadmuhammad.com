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

Citation count (`232`) and publication count (`18`) each appear in three places:
the hero stat block, the Evidence index row for scholarly articles, and the
Publications section intro. Update all three together.

The Publications section lists 14 papers with full citation details out of the 18
on Google Scholar, and is labelled "selected work" for that reason. Add the four
missing entries and the label can be dropped.

## Design notes

Accent colours are the two LED spectra that won the WisDOT field study:

- `--beam: #2C8FFC` — Blue Baseline, controller RGB 129 / 420.75 / 741 on the 0–750 scale
- `--ice: #1BB1FF` — Ice Blue, controller RGB 80 / 520 / 750
- `--halogen: #F2B23E` — the 4000 K neutral-white reference it outperformed

Display face is Overpass, which is based on FHWA Highway Gothic — the lettering used
on US road signs. Body is IBM Plex Sans; data and labels are IBM Plex Mono.

## Proposals section

`#proposals` lives at the end of the Roles section. Six proposals are listed; only the
WisDOT crosswalk entry is marked "Awarded & delivered" — the other five say "Submitted".
Correct any that were awarded, declined, or are still in preparation by editing the
fourth column. The `class="win"` on a row is what gives it the blue highlight, so move
that attribute if another proposal gets funded.

The accelerated-computing vendor challenge is described generically rather than by name,
per your instruction not to name target companies on the site. Since this is proposal
work you actually did rather than a pitch, naming it is defensible if you prefer —
edit the "Program / sponsor" cell.

## Still to confirm

1. **NSF I-Corps** — written as I-Corps (Milwaukee I-Corps program, five workshops).
2. **Tsinghua master's dates** — omitted on the site because the LinkedIn dates
   conflict with the listed engineering roles. Fix on LinkedIn, then add here.
3. **Peer review** — currently generic. Add specific journal / conference names.
4. **IEEE membership grade** — Member, Senior Member, Student Member.
5. **h-index / i10-index** — omitted pending current Google Scholar figures.
6. **WisDOT award amount** — shown as ~$125K, sourced from the Digital Journal interview.
