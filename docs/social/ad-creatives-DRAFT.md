# Client+ ad creatives (DRAFT)

**Status:** DRAFT, awaiting Ryan sign. Nothing has been created in Meta Ads Manager or LinkedIn Campaign Manager, and no spend is set. Ryan signs all ad copy and all spend.
**Advertiser:** Facebook Page "Client+ Case Management". LinkedIn variants need a Client+ LinkedIn Page first (none exists yet).
**Link rule:** destination is `[LINK: marketing page after PR #2 merges]`. Until PR #2 merges, use a "Send Message" objective or hold the ads.
**Guards:** contact is (775) 722-7725 (call or WhatsApp) (no old github.io page URL); flat $10,000 per organization, no cap; teams of 3 to 30 staff; features limited to the synthetic-data demo; no compliance-certification claim; do not use the word HIPAA in ad copy (lead with row-level security and MFA instead); BAA and per-customer AWS hosting in future tense; trial only as "Ask us about a free 30-day trial"; no customer names, counts or testimonials.

## Creative A — "One place for your casework"

**Meta (Facebook and Instagram feed)**
- **Primary text:**
  > Client records, case notes, kiosk check-in and grant tracking in one system, built for nonprofit teams of 3 to 30 staff. One price: $10,000 per organization, with no per-seat fees. Ask us about a free 30-day trial: (775) 722-7725 (call or WhatsApp).
- **Headline:** Case management for small nonprofits
- **Description:** $10,000 per organization. Teams of 3 to 30.
- **CTA button:** Learn More (after PR #2 merges) / Send Message (before)
- **Visual:** Single image, 1080x1080. Left: a laptop showing the Client+ client record with a case-note timeline (synthetic demo data, "Demo data" label). Right: three short lines with check marks: "Client records + case notes", "Kiosk check-in", "Grant tracking". Brand colors, no people photos.

**LinkedIn variant (Sponsored Content, single image)**
- **Intro text:**
  > Executive directors and program managers: if your casework lives in spreadsheets and shared drives, Client+ puts client records, case notes, check-in and grant tracking in one system. Built for nonprofit teams of 3 to 30 staff. $10,000 per organization. Ask us about a free 30-day trial: (775) 722-7725 (call or WhatsApp).
- **Headline:** Case management built for small nonprofit teams
- **CTA:** Learn More (destination `[LINK: marketing page after PR #2 merges]`)
- **Visual:** Same image as Meta, 1200x627 crop.

## Creative B — "Security your funders will ask about"

**Meta (Facebook and Instagram feed)**
- **Primary text:**
  > Your clients trust you with sensitive information. Row-level security, and MFA available on every login. We will sign a business associate agreement before any real client data goes in. $10,000 per organization, for teams of 3 to 30. Questions? (775) 722-7725 (call or WhatsApp).
- **Headline:** Client data, locked down
- **Description:** Row-level security and MFA, built in.
- **CTA button:** Learn More (after PR #2 merges) / Send Message (before)
- **Visual:** Single image, 1080x1080. A simple illustration of a client file with a padlock, three staff icons each seeing a different set of records, and a phone showing an MFA code. Text overlay: "Row-level security + MFA". No people photos, no real data.

**LinkedIn variant (Sponsored Content, single image)**
- **Intro text:**
  > Small nonprofits handle health, housing and family information too. Row-level security, and MFA available on every login. We will sign a business associate agreement before any real client data goes in. Built for teams of 3 to 30 staff. $10,000 per organization. Questions? (775) 722-7725 (call or WhatsApp).
- **Headline:** Row-level security and MFA on every login
- **CTA:** Learn More (destination `[LINK: marketing page after PR #2 merges]`)
- **Visual:** Same illustration, 1200x627 crop.

## Review notes for Holdings Engineering

- Per the review of 9715810, the word HIPAA is not used in any ad headline, primary text, description or image text. Creative B now leads with the controls: "Row-level security, and MFA available on every login. We will sign a business associate agreement before any real client data goes in."
- Neither creative mentions per-customer AWS hosting. If Ryan wants it, it goes in as "will run in your own AWS account" (future tense).
- Meta may still review health-related wording because Creative B talks about sensitive client information. The word HIPAA was dropped from ad copy to avoid a compliance claim and to reduce that review risk.
