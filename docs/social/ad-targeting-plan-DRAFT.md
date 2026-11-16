# Client+ ad targeting plan (DRAFT)

**Status:** DRAFT, awaiting Ryan sign. Nothing has been set up in Meta Ads Manager or LinkedIn Campaign Manager. **No budget or spend is decided. Ryan sets every number.**
**Goal:** reach nonprofit staff, program managers and executive directors at organizations of roughly 3 to 30 staff. Ryan wants ads in all markets, so the plan is a priority-state layer plus a US-wide layer.
**Creatives:** `ad-creatives-DRAFT.md`. **Destination:** `[LINK: marketing page after PR #2 merges]`. Until PR #2 merges, use a Messages objective or hold the ads.
**Contact in ads:** (775) 722-7725 (call or WhatsApp).

## Where the priority states come from

Source: the outreach tracker CSVs on branch `campaign-drafts` (read only): `campaign/nonprofit-outreach.csv` and `campaign/foundation-outreach-week1.csv`, read at commit `e3928a3` (2026-11-16 PT). `campaign/foundation-tracker.csv` holds only an example row.

- Emailed orgs since 2026-10-22: outreach has reached **all 50 states** (no DC). That is why the plan treats every state as covered and adds a US-wide layer.
- Counting emailed orgs that did not decline, ask not to be contacted, close, or only bounce (the same list as `cross-like-targets-DRAFT.csv`, 676 orgs, 33 with no state recorded), the states with the most outreach are:

| Tier | States (emailed orgs in list) |
| --- | --- |
| Priority 1 (16+ orgs) | CA (30), IN (27), MI (23), CO (18), OH (18), NY (17), PA (16) |
| Priority 2 (13–15 orgs) | KS (15), KY (15), WV (15), TX (14), WA (14), GA (14), IA (13), LA (13), ME (13), TN (13), NE (13), MS (13) |
| Priority 3 (all other states, 7–12 orgs each) | AK, AL, AR, AZ, CT, DE, FL, HI, ID, IL, MA, MD, MN, MO, MT, NC, ND, NH, NJ, NM, NV, OK, OR, RI, SC, SD, UT, VA, VT, WI, WY |

Why weight by outreach volume: people at orgs that got an email may see the ad and recognize the name (retargeting by email list is **not** proposed; see below).

## Campaign structure (proposal)

1. **Priority states** (Priority 1 + 2): one ad set per platform, states as location targets, both creatives.
2. **US-wide**: one ad set per platform, all 50 states, Priority 1 + 2 states excluded so the two ad sets don't compete.
3. Optional later: lookalike or website retargeting once the marketing page is live and has a pixel or Insight Tag. That needs Ryan's approval and a privacy-policy update first.

**Not proposed:** uploading the outreach email list as a Custom Audience or Matched Audience. Those contacts did not opt in to ads, and several are personal addresses. Ryan can decide otherwise, but the default is no.

## Meta (Facebook and Instagram) targeting options

- **Location:** United States; Priority ad set = Priority 1 + 2 states; US-wide ad set = all states minus those.
- **Age:** 25–65+.
- **Detailed targeting, interests (check each exists in Ads Manager at setup; Meta changes these often):** Nonprofit organization, Charitable organization, Social work, Case management, Human services, Philanthropy, Grant writing, Fundraising, Volunteering, TechSoup, National Council of Nonprofits, Community Action Agency, Homelessness, Addiction recovery, Domestic violence awareness, Reentry.
- **Detailed targeting, job titles and employers (availability varies; verify):** Executive Director, Program Director, Program Manager, Case Manager, Case Management Supervisor, Director of Operations, Grants Manager, Development Director, Clinical Director, Office Manager (nonprofit).
- **Narrowing (if audience is too broad):** require one nonprofit interest AND one job-title or role signal.
- **Advantage+ audience:** reasonable to test against detailed targeting in the US-wide ad set only, so the priority ad set stays readable.
- **Placements:** Facebook Feed, Instagram Feed, Facebook Marketplace off by default.
- **Policy note:** Creative B mentions HIPAA. Meta may review health-related wording more strictly. Not a special ad category (not housing, employment, credit or politics).

## LinkedIn targeting options

Needs a Client+ LinkedIn Page first (none exists yet).

- **Location:** same two layers as Meta.
- **Company industry:** Non-profit Organizations; Individual and Family Services; Civic and Social Organizations; Mental Health Care; Community Services; Philanthropic Fundraising Services (for foundations).
- **Company size:** 2–10 and 11–50 employees. LinkedIn's bands don't match 3 to 30 exactly; 2–10 plus 11–50 is the closest fit and will include some orgs outside the range.
- **Job titles:** Executive Director, Program Director, Program Manager, Director of Programs, Case Manager, Case Management Supervisor, Director of Operations, Operations Manager, Grants Manager, Development Director, Clinical Director, Chief Executive Officer (nonprofit).
- **Job functions (alternative to titles):** Community and Social Services; Program and Project Management; Operations.
- **Seniority:** Owner, CXO, Director, Manager.
- **Exclude:** job function Sales (vendors), and employees of large health systems if they show up.
- **Audience size check:** LinkedIn recommends audiences above a minimum size; if a priority-state audience is too small, widen titles before widening company size.

## Example budget structure (PROPOSAL ONLY — Ryan sets all amounts)

No dollar amounts are decided. The split below is a starting shape for Ryan to fill in.

| Ad set | Share of total (example) | Daily amount |
| --- | --- | --- |
| Meta — Priority states | 40% | `$[RYAN SETS]` |
| Meta — US-wide | 25% | `$[RYAN SETS]` |
| LinkedIn — Priority states | 25% | `$[RYAN SETS]` (check LinkedIn's daily minimum) |
| LinkedIn — US-wide | 10% | `$[RYAN SETS]` |

- Run 7 to 14 days, then review cost per message or click and move budget toward what works.
- Lifetime cap per campaign so nothing overspends: `$[RYAN SETS]`.
- Payment method and ad account are Ryan's. No agent adds a card or launches a campaign.

## Honesty

- Docs only. Nothing was created, scheduled, published or spent.
- State counts come from the public outreach trackers on `campaign-drafts` as of 2026-11-16 PT and will drift as outreach continues.
- Interest and job-title options are not verified live in Ads Manager or Campaign Manager in this pass.
