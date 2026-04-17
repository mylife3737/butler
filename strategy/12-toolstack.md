# Toolstack

Every tool named here is either free or fits within the $1,000 budget. Every tool has one named owner; credentials are stored in a shared password manager (Bitwarden free) rather than a single human's brain.

---

## Core stack (Sprint 0 signup required)

### 1. Email & calendar — Google Workspace (free)
Sign up for a Gmail account: **butlerforflorida@gmail.com** (or similar) — use this ONLY for campaign. Keep personal accounts separate.
- Owner: campaign manager.
- Cost: free.

### 2. Campaign phone — Google Voice (free)
- Setup: [voice.google.com](https://voice.google.com)
- Tie to the campaign Gmail account.
- Use: published campaign phone on literature, website, voicemail for press.
- Cost: free (US calling/texting).
- Owner: campaign manager or comms lead.

### 3. Website — Cloudflare Pages (free) + purchased domain
- Domain: cynthiabutlerforflorida.com or cynthiaforfl75.com (~$15/year via Cloudflare Registrar).
- Hosting: Cloudflare Pages free tier (unlimited bandwidth).
- Build: Canva can export a simple static site, OR use a Jekyll/Hugo template pushed via GitHub.
- Required pages: Home, About (Cynthia's story), Issues, Donate (ActBlue embed), Events, Volunteer (form), Contact, Disclaimer footer on every page.
- Owner: digital lead.

### 4. Donations — ActBlue (free — 3.95% transaction fee)
- Setup: [secure.actblue.com/entities/add](https://secure.actblue.com/entities/add)
- Required: campaign legal name, treasurer contact, depository bank info, EIN.
- Owner: treasurer.

### 5. Email marketing — Mailchimp Free (→ 500 contacts) or Buttondown ($0-10/mo)
- **Mailchimp Free:** up to 500 contacts, 1,000 sends/month. Sufficient for Sprint 0-2. Upgrade or migrate when list crosses 500.
- **Buttondown (alternative):** cleaner UX, $9/month for up to 1,000 subscribers.
- Owner: comms lead.
- Transition plan: when list approaches 500, evaluate EveryAction / Action Network (political-campaign-specific, integrates with voter file).

### 6. CRM — Google Sheets (starter tier)
- Template columns: Name, Email, Phone, Address, Source, Segment, Last Contact, Next Action, Donation history, Volunteer flags, Notes.
- Upgrade path: when tier-up allows, migrate to Action Network or EveryAction.
- Owner: digital lead.

### 7. Design — Canva Free (→ Canva Pro $15/mo if needed)
- Templates: yard signs, palm cards, social graphics, email headers, one-pagers.
- Maintain a "Butler for Florida" Canva team so all assets stay in one place.
- Owner: social media lead.

### 8. Video — CapCut Free (phone app) or DaVinci Resolve (desktop free)
- Editing: CapCut for short-form (TikTok/Reels/Shorts); DaVinci for longer content.
- Captioning: CapCut auto-captions (essential — 85% of FB video is watched muted).
- Owner: social media lead.

### 9. Social scheduling — Meta Business Suite (free) + manual for others
- Facebook + Instagram: schedule through Meta Business Suite.
- TikTok, Threads, Bluesky, X: manual posting (each platform's scheduler is adequate).
- Owner: social media lead.

### 10. Password manager — Bitwarden Free
- Create a shared vault for the campaign.
- All credentials go here; nothing in email, Slack, or a spreadsheet.
- Owner: campaign manager.

### 11. Communications — Signal (free) or free Slack
- Team chat: **Signal group preferred** for sensitive discussions; Slack free tier for broader volunteer coordination.
- Public comms to supporters: email + text, not Slack.
- Owner: manager.

### 12. Voter file + door app — Minivan (free with VAN access)
- **Access path:** Florida Democratic Party provides VAN access to qualified Democratic candidates.
- Alternative (if FDP access delayed): buy per-county voter file extracts from Charlotte + Sarasota SOEs (see `../research/01-district-fact-sheet.md §G`), load into a free alternative like NGP VAN's Minivan substitute or [Controlshift](https://www.controlshift.app/) for basic turf.
- Owner: field captain.

### 13. File storage — Google Drive (free → Workspace $6/user/month if needed)
- Structure: `/Admin`, `/Strategy`, `/Assets (photos, logos)`, `/Events`, `/Press`, `/Finance`, `/Volunteers`.
- Owner: manager.

### 14. Forms / intake — Google Forms (free)
- Volunteer signup form, event RSVP, donor intake, canvass intake (on paper → digitized).
- Owner: volunteer coordinator.

### 15. Analytics — Platform-native + Plausible (optional, $9/mo)
- Facebook Insights, Instagram Insights, Mailchimp Reports, ActBlue dashboards.
- Plausible for website — privacy-friendly + simpler than Google Analytics if budget allows.
- Owner: digital lead.

### 16. P2P texting (Tier 1 tier-up) — Strive or ThruText
- Already detailed in `08-budget.md`. Deploy when $500 cumulative raised.
- Owner: digital lead.

---

## Signup sequence (Sprint 0 day-by-day)

**Day 1:** Gmail account + Google Voice + Bitwarden.
**Day 2:** IRS EIN + campaign bank account open.
**Day 3:** DS-DE 9 filed with DOE.
**Day 4:** ActBlue entity created.
**Day 5:** Domain registered + Cloudflare Pages set up.
**Day 6:** Mailchimp account + first list import (25 personal contacts).
**Day 7:** Facebook page + Instagram created; Canva team set up; CRM spreadsheet template populated.

---

## Credential storage rules

- Every login stored in Bitwarden with at least one additional owner besides the person who set it up.
- When a volunteer changes roles or leaves, immediately rotate shared credentials.
- **Two-factor authentication on everything that supports it** — especially email, ActBlue, Mailchimp, Facebook, bank.

---

## Browser + device hygiene

- Cynthia's personal browser logged into campaign accounts: acceptable but requires 2FA.
- A dedicated campaign laptop is ideal by Sprint 2. A supporter-donated used machine works fine.
- Never paste credentials into chat tools.

---

## Costs summary (Sprint 0 → Sprint 5)

| Tool | Sprint 0 | Sprint 1-5 | Total |
|---|---|---|---|
| Domain | $15 | $0 | $15 |
| Google Workspace (if upgraded) | $0 | $0 | $0 |
| Canva Pro (1 month, optional) | $0 | $15 | $15 |
| Mailchimp (when list > 500) | $0 | $0-$50 | $0-$50 |
| Buttondown (alternative) | $0 | $0-$90 | $0-$90 |
| Plausible | $0 | $0-$45 | $0-$45 |
| Bitwarden | $0 | $0 | $0 |
| Signal / Slack Free | $0 | $0 | $0 |
| ActBlue | $0 | 3.95% of donations | — |
| Strive / ThruText (Tier 1 unlock) | $0 | per-message | — |

Budgeted total in `08-budget.md` Tool line: **~$30** (domain + optional Canva Pro month). Everything else is free tier.
