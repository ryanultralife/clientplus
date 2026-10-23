# Client+ National Campaign Plan (DRAFT)

Status: internal draft for Ryan's sign. Nothing here has been sent or published. Owner: Client+ Product. Peers: Client+ Social (posts), Holdings Engineering (claim review). Questions for Ryan go through Holdings Engineering, and Cofounder brings them to him.

## Goal
Make Client+ a main funding path. The way there is to sign the first 5 founding clients, then run a national push through the networks that small human-services nonprofits and their funders already trust.

## Who we're selling to
1. **Small human-services nonprofits** (3 to 30 staff) that run case management on spreadsheets, paper, or a tool that's too expensive. Typical programs are reentry, crisis, homelessness, family support, behavioral health support, and youth.
2. **Foundations and funders that pay for that work**: community foundations, United Way chapters, capacity-building funders, and state and county contract funders. The pitch to them is that Client+ is a better use of their money than per-seat software licenses or a grant-funded data clerk. They pay once, the grantee owns its data and reports, and the system keeps working after the grant ends.

## Offer
- **Founding price: $10,000 one-time deployment** for the first 5 clients, and $20,000 after that (Ryan, 10/22). In return the client gives feedback and sits in on monthly product calls. With their written OK, they may also be referenced (no names until they consent).
- Everything else stays as listed: no per-seat fees, support sold in prepaid 10-hour blocks, optional modules, and hosting at cost.
- **Future tense, by rule:** each customer *will* get its own AWS account. We *will* sign a business associate agreement (BAA) and a customer agreement before any real client data goes in. No second-customer stand-up is live today.

## Sequence (gated, in order)
1. **PR #2 merges** (page honesty fix). Until then nothing links to the public page. Ryan signs.
2. **Sign the first 5 founding clients.** We find them through warm introductions, the state association in our home region, and regional funders. Each signing needs Ryan's sign-off on the pricing offer, the agreement, and the deploy.
3. **Build the HIPAA pack** before any real client data:
   - a BAA template (reviewed by counsel, not written by a bot as final),
   - a 2-page security summary covering per-org AWS account, encryption, role-based access enforced in the database, 2-factor login, the audit trail, backups, and the rule that AI gets no client data,
   - a customer agreement template that includes the guarantees on data export and on what happens if Client+ shuts down.
4. **National push** after steps 1 to 3 are done:
   - **State nonprofit associations:** member-benefit listings, member webinars, and conference sessions. Start in the West, then go national through the National Council of Nonprofits network.
   - **Grant-funded case-management programs:** reentry, homelessness/CoC, and behavioral-health contracts. We'd map Client+ reports to the funders' required fields, with no claims of being certified on any state system.
   - **Foundations:** capacity-building grant cycles, using a one-page budget justification grantees can drop into a proposal.
   - **Social:** LinkedIn and Facebook drafts from Client+ Social. Nothing goes up until Ryan has Business Manager and LinkedIn access and signs each post.

## Weekly foundation targeting (100/week)
Draft process. Nothing is sent by a bot.

- **Sourcing (public sources only):** IRS 990-PF filings via ProPublica Nonprofit Explorer, Candid where publicly accessible, foundations' own websites and published grants lists, and state/regional grantmaker associations. Record the source URL for every entry.
- **Fit criteria (score each 0-5, note why):** funds human services or case management; gives to small nonprofits; typical grant size fits a $10,000 deployment; geography matches where Client+ will serve (see decision 3); open to technology or capacity-building grants.
- **Contact:** one named public contact per foundation, taken from their published grants or program contact. No scraped personal emails, no guessed addresses.
- **Weekly cadence:** Monday source and score ~100 foundations into `campaign/foundation-tracker.csv`; Tuesday-Wednesday create drafts for qualified rows; Ryan reviews and sends through the week; Friday log replies and next steps.
- **Sending:** outreach sends from ryanvukich@gmail.com. Drafts are created only in that account's Gmail Drafts, using Email 2 in CAMPAIGN-COPY-DRAFT.md. Ryan reviews and sends each one himself. No bot sends.
- Gated like everything else: no outreach until PR #2 merges and Ryan approves the outreach.

## Proof points
- Origin: built inside a reentry and crisis-services nonprofit in rural Northern California.
- First customer reference: **[PCIRC — needs Ryan approval]**. Placeholder only, with no name, quote, or testimonial.
- Synthetic-data demo only. No screenshots of real records.

## Metrics (first 90 days after PR #2 merges)
- founding-client conversations booked
- founding clients signed (target: the first 5)
- HIPAA pack complete (BAA template, security summary, customer agreement)
- association or funder channels secured (listings, webinars, intros)
- demo-to-proposal rate

## Decisions Ryan has to make (routed through Holdings Engineering)
1. Merge PR #2.
2. ~~Approve founding pricing~~ DECIDED (Ryan 10/22): $10,000 for the first 5 clients, $20,000 after that.
3. Decide whether Client+ will serve outside Northern California. The page still says North State.
4. Confirm he's ready to stand up a per-customer AWS account for each founding client.
5. Choose counsel for the BAA and customer agreement templates.
6. Get Business Manager and LinkedIn access for Client+ Social.
7. Decide whether PCIRC can be named or quoted at all.

---
**Honesty block**
- Tested: content checked by hand against the current page (master `4f0244b`) and PR #2. Charter name guard checked. No PHI.
- CI: none (docs only).
- NOT verified: no BAA or customer agreement exists, no per-customer AWS stand-up has been done, no contacts are verified, and nothing has been sent or published.
