# USAspending grant-recipient list — NOTES + starter sample

**Status:** Draft methodology + small public starter sample. This is a **lead list**, not a send list. Any email sends go through the existing outreach lane and its bounce stop.  
**Updated:** 2026-11-05 PT · Client+ Social  
**API used:** `POST https://api.usaspending.gov/api/v2/search/spending_by_award/` (public). Sample pulled 2026-11-05 PT.

## Fit criteria (Client+)

- Human-services / case-management adjacent work (homelessness, reentry, crisis, family support, behavioral health, youth).
- Target org size **3 to 30 staff** — **USAspending does not publish staff counts.** Size must be verified later from public 990 / org sites (e.g. ProPublica Nonprofit Explorer) before outreach.
- Prefer assistance awards in a usable founding-seat range; sample below used award amounts roughly $25k–$500k as a first cut, not a pricing claim.
- Public org names and awarding agencies only. No PHI, no personal emails scraped here.

## Method

1. Query USAspending assistance awards (`award_type_codes` 02–05) with keywords such as `homelessness`, `reentry`, `domestic violence`, `behavioral health`, `case management`.
2. Deduplicate by recipient name.
3. Drop obvious non-fits in a later pass (large hospital systems, universities, city/county governments when the buyer is not a small nonprofit, foreign recipients).
4. Enrich off-branch or in a later commit: public website, published info@ / grants contact, state, estimated staff (VERIFY), source URL.
5. Hand qualified rows to the outreach lane; Social does not create Gmail drafts.

## Starter sample (raw API, lightly curated)

See `usaspending-sample-leads.csv`. Rows marked `needs_size_verify=yes`. Government and large-system recipients are tagged `likely_skip` so outreach does not waste sends.

## Limits / honesty

- Keyword search is noisy; several housing-counseling and CoC awards appear beside true small nonprofits.
- Staff size, email, and "already contacted in campaign CSVs" are **not** checked in this file. Before any send, cross-check Product/Holdings `campaign-drafts` outreach CSVs (read-only for Social) for do-not-contact.
- No messages were sent from this work.
