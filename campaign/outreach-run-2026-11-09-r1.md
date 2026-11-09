# Client+ outreach RUN 1 of 2 — 2026-11-09 PT

Account: ryanvukich@gmail.com. Window: 7:19:48–7:44:58 AM PT. Pace: >=58s between sends.

## Pre-checks
- Gmail Sent since 11/6: last outreach send was 11/6 8:00 AM PT (11/6 run 1). 11/6 run 2 never happened; nothing sent 11/7–11/9 before this run. Today's count before run: 0.
- Drafts titled 'Founding Client+ seats for your grantees': none. Drafts consumed: 0.
- Known list rebuilt (box /workspace/cp1109/known.txt, 460 addrs + domain check + name/state check vs tracker).
- Older DSN: Family Crisis Center GA (info@thefamilycrisiscenter.org) went to PERMANENT failure 11/7 12:35 PM PT -> tracker marked do-not-retry (not counted in today's bounces).

## Sent: 24 (15 NP + 9 F)
First: 1a1c0e4e56a3c5d2 (Adams County CF). Last: 1a1c0fbe24613c02 (Lee Conlee House). Full list in tracker CSVs (sent date 2026-11-09).

## ERROR
- Send #1 (Adams County Community Foundation, accf@adamscountyfoundation.org, msg 1a1c0e4e56a3c5d2) went out with the stale b0.txt copied from cp1106: greeting and first line say "Grant County Community Foundation". Rest of copy correct. No correction sent (would be a follow-up). Ryan to decide whether to send a one-line correction. All later bodies regenerated from plan.json and the greeting checked before each send.

## Bounces today: 3 -> RUN STOPPED (day closed)
1. info@projectmore.org (Project MORE CT) 550 5.4.1 Access denied (Outlook) 7:25 AM PT
2. info@bvadvocacycenter.org (BVAC RI) Office 365 Undeliverable, forwarding to info@bvacri.org failed, recipient unknown 7:35 AM PT
3. brooksv@leeconleehouse.org (Lee Conlee House FL) 550 5.4.1 Access denied (Outlook) 7:44 AM PT
All three marked DO NOT RETRY in the tracker. 3-bounce limit hit, so run 2 should NOT send today.
Pattern: 2 of 3 were Outlook "550 5.4.1 Access denied" (directory-based edge blocking). Future runs could deprioritize Outlook-hosted addresses or put them last.

## Replies
- Inside Out Peer Services (MT), Jessica Colton, 11/8 3:34 PM PT: "Yes, I would be interested to hear you out." Interested / trial lead. Not answered (bots don't reply).
- No new 'no thanks' since 11/6. Earlier: Westmoreland CF 'No thanks' (already DNC); Safe Haven auto-reply (11/6).

## Queue left (queue_run2.json) — for next weekday since today is closed
- F Community Foundation for the Greater Capital Region NY info@cfgcr.org (researched, not sent: stopped at 3 bounces)
- F Community Foundation of Orange and Sullivan NY admin@cfosrny.org (verify domain)
- NP Amos House RI info@amoshouse.com (check size)
