# Voter Targeting — Voter File, Turf, and VBM Chase

In an R+28 district with a $1,000 budget, targeting discipline is the difference between a 15-point loss and a 25-point loss. Every contact that doesn't land on a persuadable voter is a wasted contact.

---

## Step 1 — Get the voter file

### Path A (preferred): Florida Democratic Party + VAN access
Many Democratic candidates qualify for free VAN access through their state party once qualified for the ballot. This includes:
- Statewide voter file with party, history, VBM status.
- Minivan app (free) for door-knocking.
- Persuadability / turnout scores (models).

**Action:** Cynthia applies to FDP for candidate access immediately after filing DS-DE 9. Cooperation with Charlotte + Sarasota DECs helps — ask the DEC chairs to vouch.

### Path B (backup): County voter file request
If FDP access is delayed or denied:
- **Charlotte County SOE:** charlottevotes.gov (verify URL) — request voter file extract for Charlotte County voters in HD 75. Usually provided on USB drive or as a CSV download for a nominal fee (~$25-$50).
- **Sarasota County SOE:** sarasotavotes.gov — same process for the portion of HD 75 in Sarasota County (Englewood-area precincts).

**What the voter file includes (public record per F.S. 97.0585):**
- Name, address, party registration, year of birth (NOT full DOB publicly).
- Vote history (not who they voted for — just whether they voted in each election).
- VBM request history.
- Precinct assignment.

**What's NOT in the file:**
- Phone numbers (unless voter provided at registration — spotty).
- Email addresses (never).
- Issue preferences.

### Path C (free backup): county-published precinct-level data
Both SOEs publish precinct-level turnout data free on their websites. Enough to identify "high-D-turnout" and "low-D-turnout" precincts at a macro level.

---

## Step 2 — Segment the universe

Once the file is loaded into a spreadsheet or Minivan:

### Segment A — **Turnout universe** (already-committed D votes; GOTV is the lever)
- Registered Democrats who voted in the 2022 or 2024 general elections.
- Estimated HD 75 size: 12-15K voters.
- Action: email + door + VBM chase. Don't spend time "persuading" them.

### Segment B — **Persuadable NPA** (the swing)
- No Party Affiliation voters who voted in recent general elections (propensity).
- Tie-breakers favoring persuadability:
  - Female voters (historically more persuadable on D candidates).
  - Younger (under 45) voters.
  - Newly registered voters (since 2022 — not yet hardened).
- Estimated HD 75 size: 8-12K.
- Action: door + earned media + testimonial content. Tell the story; don't ask for the vote until Sprint 4+.

### Segment C — **Soft-R crossover** (split-ticket)
- Registered R who supported Amendment 4 / Amendment 3 — ⚠️ hard to identify from voter file directly; use precinct-level A4/A3 win margins as a proxy to identify precincts where crossover is viable.
- Also: R voters with history of non-participation in primaries (suggests weaker partisan identity).
- Estimated HD 75 size: 3-5K.
- Action: selective door with a biography-first message (don't lead with "Democrat"). LTE presence in their daily paper.

### Segment D — **Hard-R base** (do not contact)
- Registered R with 100% primary participation history.
- Estimated size: 20-25K.
- Action: **none.** They're not our universe. Resource discipline.

### Segment E — **Low-propensity D** (need to register to vote / VBM-request)
- Registered D with sporadic voting history.
- Estimated size: 5-8K.
- Action: voter registration drive + VBM request drive + repeat contact in Sprint 5.

---

## Step 3 — Cut turf by precinct

**Goal:** assign every likely canvass household to a precinct, group precincts into walkable "turfs" of 50-100 households, and let volunteer pairs own one turf each week.

**Minivan workflow (if VAN):**
- Filter voter file by district + turf criteria.
- Auto-generate walk lists with optimal walking order.
- Volunteers use the app to log conversations.
- Data syncs back centrally.

**Manual workflow (if no VAN):**
- Export voter file to Google Sheets.
- Filter by precinct + segment.
- Sort by street address.
- Print walk lists by precinct as 1-page PDFs.
- Volunteers use paper + pen; digital lead re-enters data each week into CRM.

**Turf priorities (in order for Sprints 2-3):**
1. Highest-D-share precincts with LOW turnout history (base activation).
2. High-NPA precincts with recent general-election turnout (persuasion).
3. Soft-R crossover precincts (Amendment 4 + homeowner-insurance-complaint heavy).
4. Newly-developed precincts (Wellen Park, parts of Port Charlotte) — mixed persuasion + voter registration.

---

## Step 4 — Canvass script (persuasion version)

**Duration:** 3-5 minutes max per door.

> "Hi, I'm [volunteer name], a neighbor. I'm here on behalf of Cynthia Butler — she's running for our state house seat. Have you heard of her?"
> 
> [If NO:] "She's a retired paramedic and a nurse from here in HD 75. She's running as a Democrat against the current state rep, Danny Nix. What's on your mind this year — what matters most in the state house?"
>
> [Listen. LISTEN. Take notes.]
>
> [Based on what they said, tie Cynthia's story to it. If insurance: "Cynthia's been fighting insurance denials in her own family. She's running because she's sick of it." If schools: "Cynthia put herself through school while on assistance — she knows what a good public school saved her." If Ian/storms: "Cynthia was working EMS calls during Ian. She knows what the recovery has looked like up close."]
>
> "Two quick things before I go:
> 1. Can I get your email? We'll send one short update a week. No spam. You can unsubscribe anytime.
> 2. Would you like a vote-by-mail ballot? In Florida you have to request it fresh every 2 years. I've got the form right here; takes 30 seconds."

**Intake form fields (paper):**
- Address, voter name(s), party
- Email (with opt-in checkbox)
- Phone (with text opt-in checkbox)
- Top issue mentioned
- Support indicator (strong Y / lean Y / undecided / lean N / strong N / refused)
- VBM request signed (yes/no)
- Volunteer interest (yes/no)
- Notes

---

## Step 5 — VBM chase program (critical in FL post-2021)

**The law (SB 90, 2021; amended since):** Florida VBM requests expire at the end of the general election cycle following the request. Practically: **every voter must re-request VBM every 2 years.** Voters who had VBM in 2024 must request again for 2026.

**Therefore:** every door the campaign knocks, every phone call, every event booth includes a VBM request card as a core tool.

### Charlotte County VBM request
- Online: charlottevotes.gov (verify URL) → "Request a mail ballot."
- Paper: download form from SOE site, hand out at every event; include a stamped return envelope for super-voter households.
- Deadline: ~12 days before election (⚠️ verify 2026).

### Sarasota County VBM request
- Same approach; sarasotavotes.gov.

### Chase cadence
- Sprint 3 (July-Aug): every canvassed household receives a VBM card + script.
- Sprint 4 (Sept): text + email campaign to every opted-in supporter, "have you requested your VBM ballot yet?"
- Sprint 5 (Oct): track returned-ballot status from SOE daily reports. Contact every Dem / persuadable-NPA who has REQUESTED but not RETURNED a ballot. Target: >80% return rate among campaign-touched voters.

**Ballot return tracking:** both Charlotte and Sarasota SOE publish daily VBM-returned data by voter. This is the gold of the closing weeks. Digital lead pulls each morning, updates CRM, assigns calls/texts/doors to chase the non-returners.

---

## Step 6 — Refusing the hard-R opportunity cost

Every hour spent knocking a door in a hard-R precinct is an hour NOT spent in persuasion territory. **The single most common reason challengers lose by more than polling predicted:** they felt obligated to "campaign everywhere" and diluted their targeting.

Rule: if Sprint 2's canvass data shows the turf assignments are drifting into hard-R precincts (by accident or by volunteer preference), field captain re-cuts the turf and reassigns. This is a monthly audit.

---

## Research debt (before Sprint 2)

- [ ] Confirm FDP access is granted or Path B activated.
- [ ] Voter file loaded into a tool (Minivan or Sheets).
- [ ] Precinct-level Amendment 4 / Amendment 3 results pulled (Charlotte + Sarasota) to identify crossover precincts.
- [ ] Turf map printed for Sprint 2's first 4 canvass weekends.
- [ ] Every canvass intake form printed in bulk.
- [ ] VBM request card design locked + printed.
