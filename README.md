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

## Citation impact block

Sits directly under the hero stats (`.impact`). Three claims, each with a source label:

- **Top 1%** — labelled "Expert assessment". Replace this label with the actual
  evaluator's name and credential (e.g. "Prof. J. Smith, independent expert
  evaluation, 2026"). An attributed percentile is evidence; an unattributed one
  is an assertion, and reviewers treat the two very differently.
- **30+ countries** — labelled "Citation analysis". Name the tool if you have it
  (Scopus, Web of Science, etc.).
- **h-index 8** — labelled "Google Scholar".

### h-index: 8 or 9

Your own papers, sorted by citations: 43, 31, 30, 29, 27, 19, 18, 13, 8, 4.
The 9th has 8 citations, which is fewer than 9, so h-index = 8.

Adding the plant-biology paper (10 citations) back in makes the 9th value 10,
which gives h-index = 9. That paper was the only thing producing the 9, and you
have removed it from Scholar.

So whatever number appears here must match what Scholar shows today. Check the
profile and edit `.impact` and the hero stat label together if it has changed —
a paper currently at 8 citations gaining one more would legitimately return you
to 9.

## Send these and the page gets stronger

Each of these maps to a criterion the page currently states weakly or not at all:

1. **Peer review venues + count.** Journal and conference names, roughly how many
   manuscripts, and since when. Check your ORCID review record or editor invitation
   emails. This is the weakest section on the page right now.
2. **Invited talks and presentations.** Anything beyond TRB 2026 and the SE Wisconsin
   Symposium — guest lectures, seminars, panels, industry talks.
3. **Teaching and mentoring.** Courses taught or assisted; undergraduate or masters
   students supervised, by name and project. Mentoring is direct evidence of a
   leading role.
4. **Editorial roles.** Any technical committee membership, session chairing, or
   programme committee service.
5. **Awards detail.** For each award: the awarding body, year, number of recipients,
   and the pool competed against. "One of three selected from 400 graduate students"
   is far stronger than the award name alone.
6. **IEEE membership grade** — Student Member, Member, or Senior Member. Senior Member
   requires nomination and review, so it counts for considerably more.
7. **Expert evaluator's name and credential** for the Top 1% claim.
8. **Dataset access.** Once CrossTraj or GLANCE is downloadable, the URL — a dataset
   others can actually use is much better evidence than one only described.

## Still to confirm

1. **NSF I-Corps** — written as I-Corps (Milwaukee I-Corps program, five workshops).
2. **Tsinghua master's dates** — omitted on the site because the LinkedIn dates
   conflict with the listed engineering roles. Fix on LinkedIn, then add here.
3. **Peer review** — currently generic. Add specific journal / conference names.
4. **IEEE membership grade** — Member, Senior Member, Student Member.
5. **h-index / i10-index** — omitted pending current Google Scholar figures.
6. **WisDOT award amount** — shown as ~$125K, sourced from the Digital Journal interview.
