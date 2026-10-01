# RouteLogic Velocity, A Frontline-First Dispatch View

> Strip the admin clutter into one real-time dispatch view so fleet coordinators reroute in seconds, not screens.

**Stuart Baxter · Product Management Cohort · Sept 2026** · https://github.com/StuBax1986/pm-final-project--Stuart-Baxter/tree/main

Prototype: https://claude.ai/artifact/Wq7gYZtkmhUFzKu4fqQEBk

---

## Final Project Deliverables

### Slide 5 · Strategy
- **Problem:** # Problem Hook & Value Proposition, Module 1

- **Scenario:** RouteLogic Velocity (B2B)
- **Persona:** Persona 2 — Enterprise Ops Manager, accountable for frontline adoption and renewal (UXR-04, UXR-10)

## Strategic crisis
Frontline churn is invisible until it's fatal — daily users route around the product instead of cancelling, so dashboards stay calm while internal champions like this ops manager quietly lose confidence.
A competitor is capturing the daily workflow — every month RouteLogic stays complex, a leaner rival entrenches itself as the tool his team actually uses for dispatch and coordination.
The brand is being repositioned against you — from his seat, RouteLogic risks becoming "the expensive back-office layer" instead of the operating system it built its reputation on, and he is the one who has to defend that budget line at renewal.

## Moment of misery
He can name the problem but not fix it alone — "it does everything, which is the problem": his frontline uses maybe 5% of the product and can't find that 5% (UXR-04). Adoption data broadly supports this: frontline clusters on three features (64–88% use) and falls to single digits on the rest, though "roughly half the modules go untouched" is the more precise read than a literal 5%.
His team is abandoning workflows he's accountable for — only 18% of coordinators complete the full daily workflow, and Compliance Checks alone run 5x over benchmark (14.6 vs. 3.0 min). This is the on-the-ground evidence behind his "can't find it" complaint, not an assumption.
He is already shopping a replacement — he is evaluating a leaner competitor that "just does routing well" (UXR-04), and a regional manager has told him renewal is at risk (UXR-10). NPS has collapsed 30 points and 4 of 5 accounts now cite complexity as a churn reason — directionally strong support for his instinct, though not yet proof that his account specifically is the one at the center of it.

## Problem hook
RouteLogic built the most powerful operating system in logistics — and in doing so, buried the one workflow that actually keeps freight moving, so fast becomes complex, complex becomes churn, and churn is already sitting inside our biggest account.

## Value proposition
FOR operations managers accountable for frontline adoption and renewal, WE WILL strip away the admin and compliance clutter burying core dispatch workflows so his team's daily usage — and his renewal story — recovers before the next review, BECAUSE our largest account is already trialing a leaner competitor, and every month of delay lets them lock in that switch.

## Cold-read self-review
Strongest: The BECAUSE still lands hardest for this persona specifically — renewal risk is literally his job, and now there's data behind it (30-point NPS collapse, 4 of 5 accounts citing complexity). But "our biggest account" remains an assertion the underlying research doesn't confirm — UXR-04 and UXR-10 don't state account size or rank, so this line is doing more rhetorical work than the evidence currently supports.

Weakest: The "5%" figure in the moment of misery is a quote, not a measurement — real adoption data shows frontline using roughly half the feature set, not one-twentieth of it. Repeating "5%" verbatim risks a sharp reader catching the gap between quote and data.

Sharpen: Replace "our biggest account" with a claim the data actually backs — e.g., "an account already showing the churn pattern: 30-point NPS collapse, workflow abandonment at 82%" — and soften "maybe 5%" to "a small, hard-to-find fraction" so the hook survives a fact-check without losing its edge.
- **Value proposition:** Velocity gives coordinators one focused, real-time view, live vehicle status, exceptions, and one-tap reroute, so the tool becomes the fastest way to run the shift instead of the slowest.
- **Hypothesis:** # Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** An operations manager at an enterprise account who is accountable for whether frontline drivers and dispatchers use the platform day to day.
- **Goal , what this user is ultimately trying to achieve:** Get his frontline teams reliably using the small set of functions they need, so the platform justifies its cost at renewal.
- **Friction / moment of misery , the specific pain blocking their goal:** He sees that "it does everything, which is the problem": his frontline staff use maybe 5% of the product and can't find that 5%. He is evaluating a leaner competitor that "just does routing well." This is where complexity turns into churn risk, and UXR-10 backs it up with a regional manager saying renewal is at risk.
- **Current workaround , the external tool or manual process they rely on (M2):** Stated: rather than pushing for deeper adoption of RouteLogic, he is evaluating a leaner competitor "that just does routing well" (UXR-04) — the vendor-swap decision is his workaround for a platform his team can't get value from. Not stated: no day-to-day tool of his own appears in the notes — no adoption tracker, spreadsheet, or review cadence is described, and whether he has already run a competitor demo or is only beginning to look isn't specified. His frontline's own bypasses — texting dispatchers (UXR-01), the dispatcher WhatsApp group (UXR-02), paper manifests (UXR-12) — are workarounds happening under him, not tools he personally uses.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** RouteLogic built the most powerful operating system in logistics — and in doing so, buried the one workflow that actually keeps freight moving, so fast becomes complex, complex becomes churn, and churn is already sitting inside our biggest account.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** FOR operations managers accountable for frontline adoption and renewal, WE WILL strip away the admin and compliance clutter burying core dispatch workflows so his team's daily usage — and his renewal story — recovers before the next review, BECAUSE our largest account is already trialing a leaner competitor, and every month of delay lets them lock in that switch.

## Read your data snapshots
- **Does the low adoption confirm your persona is burdened by tools they don’t use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** His claim — "frontline uses maybe 5% and can't find it" — is directly testable against the table: drivers/coordinators cluster at 64-88% on three features and fall to 3-23% on the other three, so there is a real adoption cliff, though "half the modules go unused" is a better description than "5%." The closer match to "maybe 5%" is Financial Reporting (3% drivers, 8% coordinators), not Shift Scheduling's 42% — 42% is a middling gap, not the extreme he's describing.
- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** This is strong direct evidence for him, where it wasn't for Diego. He's not performing a personal hack — he's describing a systemic pattern — and coordinators abandoning the workflow down to 18% completion, with Compliance Checks running 5x over benchmark, is exactly the "frontline can't get through the tool" problem he's flagging to leadership.
- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona’s friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** The cell that most directly maps to his friction isn't a single score but the Reporting gap: Managers rate it 4.5 (the best score in the table) while Drivers and Coordinators rate it 1.1-1.3 (the worst). That 3.3-point spread is close to a literal illustration of "it does everything, which is the problem" — the feature he benefits from is the one his frontline can't use.

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** He sees that "it does everything, which is the problem": his frontline staff use maybe 5% of the product and can't find that 5%. He is evaluating a leaner competitor that "just does routing well." This is where complexity turns into churn risk, and UXR-10 backs it up with a regional manager saying renewal is at risk.
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** His claim — "frontline uses maybe 5% and can't find it" — is directly testable against the table: drivers/coordinators cluster at 64-88% on three features and fall to 3-23% on the other three, so there is a real adoption cliff, though "half the modules go unused" is a better description than "5%." The closer match to "maybe 5%" is Financial Reporting (3% drivers, 8% coordinators), not Shift Scheduling's 42% — 42% is a middling gap, not the extreme he's describing.
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** Persona: The enterprise ops manager (UXR-04, with UXR-10).

Role: An operations manager at an enterprise account, accountable for whether frontline drivers and dispatchers use the platform day to day.

Goal: Get his frontline teams reliably using the small set of functions they need, so the platform justifies its cost at renewal.

Friction, as confirmed across the reconciliation steps: "It does everything, which is the problem" — his frontline uses maybe 5% of the product and can't find that 5%, so he's evaluating a leaner competitor that "just does routing well," with a regional manager separately warning that renewal is at risk (UXR-04, UXR-10). Snapshots 1-3 backed the shape of this, not the letter: adoption data showed frontline using roughly half the feature set rather than a literal 5%, and the 30-point NPS collapse plus "4 of 5 accounts citing complexity" supported the churn narrative directionally, but nothing confirmed his account specifically is "the biggest" or among those four.
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** This initiative removes the gap between what RouteLogic can do and what his frontline can actually find and use, so daily adoption — not just administrative capability — becomes the reason his account renews.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Behavior change: frontline stops routing around the product and starts completing core tasks inside it — coordinators finishing the full daily workflow instead of abandoning it after Route Assignment (moving off the 18%-completion floor Snapshot 2 showed), and the ops manager shifting from evaluating a competitor to bringing usage data into the renewal conversation.

Mapping to retention/churn: this directly targets the pattern Snapshot 3 showed — NPS recovering from its -12 collapse back toward the prior +18, and fewer accounts citing complexity as a churn reason than the "4 of 5" currently reported. The revenue claim to make here is retention, not growth: protecting this account's existing recurring revenue at renewal, since nothing in the research supports an expansion or upsell case. I'd stop short of quantifying a dollar figure — the data supports a churn-risk story, not a revenue-lift number.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** Primary metric: Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2.

This is the right leading indicator because it moves on a daily/weekly cadence and sits closest to the actual friction — frontline finding and finishing the work — rather than a downstream signal like NPS or renewal that only shows up quarterly or annually. If simplification is working, this number climbs before sentiment or the renewal conversation ever reflects it; if it stays flat, nothing else in the initiative is worth reporting yet, whatever NPS does in the meantime.
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Guardrail metric: Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3).

This is the metric that must not move while the primary metric climbs, because it's the value the account actually bought (UXR-10: "the admin reporting is genuinely powerful, that's why we bought it"). Stripping clutter to speed up frontline workflows risks quietly thinning the compliance data or reporting depth managers rely on — the exact "capability being cut rather than hidden" risk already flagged in the problem-hook self-review. If Manager CSAT on these two clusters drops while coordinator completion rises, the initiative isn't simplifying the product, it's trading one churn risk for another.
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** Decision window: 6–8 weeks with a pilot cohort of coordinators (ideally including the at-risk account), long enough to get 4+ consecutive weekly readings of the primary metric rather than one noisy snapshot, short enough to inform action before the renewal date.

Thresholds, measured against the Snapshot 2/3 baselines (18% coordinator workflow completion; 3.9/4.5 Manager CSAT on Compliance/Reporting):

Scale: primary metric sustains a meaningful lift (e.g., completion holds above roughly 40–50% for 4+ straight weeks) while the guardrail holds within a small tolerance of baseline (no more than ~0.2 points off 3.9/4.5).
Pivot: primary metric improves but the guardrail drops meaningfully (more than ~0.3–0.5 points) — a sign the simplification is quietly cutting the compliance/reporting depth managers value, not just hiding clutter, so the approach needs rework rather than a straight rollout.
Kill: primary metric shows no real movement over the full window (say under a 5-point lift from 18%), regardless of what the guardrail does — evidence the lever isn't the right one, not just under-tuned.
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on UXR-04 and UXR-10's qualitative account of frontline adoption failure and renewal risk, combined with Snapshot 2's finding that only 18% of coordinators complete the full daily workflow and Snapshot 3's 30-point NPS collapse, I believe that closing the buried-workflow adoption gap for the enterprise ops manager's frontline teams will result in daily core tasks being completed in-app instead of routed around, as measured by coordinator daily workflow completion rising from 18% to at least 40%. I will protect Manager CSAT on Compliance and Reporting (currently 3.9 and 4.5) and will make a go/no-go decision after a 6–8 week pilot.

### Slide 6 · Research
- **Competitive analysis:** # Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Persona 2: The enterprise ops manager (UXR-04, with UXR-10)

Role: An operations manager at an enterprise account who is accountable for whether frontline drivers and dispatchers use the platform day to day.
- **Goal, what is this user ultimately trying to achieve?:** Goal: Get his frontline teams reliably using the small set of functions they need, so the platform justifies its cost at renewal.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** He sees that "it does everything, which is the problem": his frontline staff use maybe 5% of the product and can't find that 5%. He is evaluating a leaner competitor that "just does routing well." This is where complexity turns into churn risk, and UXR-10 backs it up with a regional manager saying renewal is at risk.
- **External tools, the outside platforms or tools the user is forced to use:** The bypass

Stated: rather than pushing for deeper adoption of RouteLogic, he is evaluating a leaner competitor "that just does routing well" (UXR-04) — the vendor-swap decision is his workaround for a platform his team can't get value from.
Not stated: no day-to-day tool of his own appears in the notes — no adoption tracker, spreadsheet, or review cadence is described, and whether he has already run a competitor demo or is only beginning to look isn't specified. His frontline's own bypasses — texting dispatchers (UXR-01), the dispatcher WhatsApp group (UXR-02), paper manifests (UXR-12) — are workarounds happening under him, not tools he personally uses.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Steps he takes

Stated: he observes that his frontline "use maybe 5% of it and can't find that 5%" (UXR-04).
Inferred: he fields frustration from drivers and dispatchers, directly or through their managers — the notes don't describe this channel.
Stated: he begins evaluating a leaner competitor "that just does routing well" (UXR-04).
Inferred: he or a regional manager raises the renewal decision internally; UXR-10 has a regional manager separately stating renewal is at risk, but the notes don't say whether his evaluation prompted that statement or the two are independent signals.
Inferred: the renewal clock keeps running in parallel with his evaluation, with no deadline stated in the notes.
- **Core frustration, the exact moment the process feels most "broken":** Where it breaks

The product's breadth becomes his liability, not his advantage — he's accountable for a platform sold on administrative depth, and the break is realizing his team can't find the narrow slice they actually need. "It does everything, which is the problem" is the exact articulation of that moment (UXR-04).
He's diagnosing a systemic problem with individual-level evidence. Nothing in the notes shows him holding account-wide usage data; "maybe 5%" is an estimate, not a report. Coordinator workflow data collected separately (18% completing the full daily process, Compliance Checks running 5x over benchmark) would support his instinct at scale, but nothing confirms he has seen it.
The fix he's reaching for bypasses the vendor entirely. Unlike Diego's texting, which still keeps the account inside the product, evaluating a competitor is an exit ramp — the workaround stops being "how we cope" and becomes "why we'd leave."
- **The evidence, a specific quote or behavior from the research that proves this:** How it feeds the business crisis

This is the same mechanism as the hook, one level up: "fast becomes complex, complex becomes churn." Where Diego's workaround is a leading indicator inside one account, this ops manager's competitor evaluation is the churn event itself starting to take shape — he is the internal champion the strategic crisis describes as "quietly disengaging" before cancellation.
Account-level data now backs his instinct, directionally: NPS has collapsed 30 points (+18 to -12), average daily time lost to manual workarounds has roughly tripled (9 to 31 minutes), and 4 of 5 accounts now cite complexity as a churn reason, up from 1 of 8 two years ago. This supports the shape of his decision, though nothing confirms his account specifically is one of the four, or that it's "the biggest."
His own reporting is the thing at risk. UXR-10 states the regional manager bought RouteLogic largely for the administrative reporting; if frontline usage keeps eroding, the data feeding that reporting erodes with it — the exact strength he'd cite in a renewal conversation may itself be getting less reliable.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** https://claude.ai/artifact/7RHe7bRJ1uAvTDRtLpH7vR — this link now shows the ops manager's future-state journey (it replaced Diego's version in place). If your submission needs a static export or zip file the way the Diego version was committed to GitHub, that export step still needs to happen on your end from the artifact page.
- **Journey map:** Shift starts → open console → hunt across admin-heavy tabs for live status → give up and switch to spreadsheet/phone (the moment of misery). Velocity surfaces a live dispatch board on open, before the coordinator reaches for the workaround.

### Slide 7 · Blueprint
- **Roadmap:** # Feature Roadmap, Module 4 · RouteLogic Velocity

**Team:** 2 engineers + 1 designer + 1 CS lead

## Strategic anchors
- **Persona:** The enterprise ops manager.
- **Primary metric:** Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2.
- **Moment of misery:** He sees that "it does everything, which is the problem": his frontline staff use maybe 5% of the product and can't find that 5%. He is evaluating a leaner competitor that "just does routing well." This is where complexity turns into churn risk, and UXR-10 backs it up with a regional manager saying renewal is at risk.
- **Guardrail:** Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3).

## Scoring
| Feature | Value | Effort | Quadrant | Decision | Rationale |
|---|---|---|---|---|---|
| B1 One-Click Compliance Checklist | 5 | 3 | Major Project | Next | At 14.6 minutes, compliance is the heaviest step in the sequence and the lowest-CSAT cluster (3.9), so it's the biggest single lever on the 18%. It needs regulatory-accuracy QA, which puts it just out of Quick Win range. |
| B2 Smart Daily Report Auto-Fill | 4 | 4 | Major Project | Next | It closes the final step of the sequence. But AI errors put Reporting CSAT (4.5) at risk, and this cluster isn't the one that's broken. |
| B3 Shift Handoff Wizard | 4 | 2 | Quick Win | Now | UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module. |
| B4 Mobile-First Coordinator Dashboard | 3 | 4 | Time Sinker | Cut | It aims at the right pain ("can't find the 5%"), but a new platform is a rebuild, not a pilot. Nothing shows mobile is where coordinators drop off. |
| B5 Step Progress Indicator | 4 | 1 | Quick Win | Now | It speaks directly to "can't find the 5%": it makes the 6-step sequence visible and tells coordinators what's next. It's the cheapest completion lever on the list. |
| B6 Driver Alert Notifications | 3 | 3 | Time Sinker | Cut | It serves drivers, not the coordinator's sequence, and adds more noise to a product whose problem is too much of everything. |
| B7 Contextual AI ETA Display | 2 | 3 | Time Sinker | Cut | Adoption is 11% and it isn't in the completion path. Surfacing more AI adds to the complexity that's driving churn. |
| B8 Fleet Analytics Manager View | 2 | 5 | Time Sinker | Cut | This is Sales pull, and it's the opposite of "just does routing well." It adds surface area and does nothing for coordinator completion. |
| B9 Compliance Audit Trail Export | 2 | 2 | Fill-In | Later | It's cheap retention insurance for the Compliance CSAT guardrail, but it doesn't move the metric. |
| B10 In-App Coordinator Training | 2 | 2 | Fill-In | Later | It treats the symptom: if the 5% needs a tutorial to find, the product should be simpler. |

## Roadmap
### NOW, Pilot (4 weeks, 3 accounts)
- **B3 Shift Handoff Wizard**, UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module.
- **B5 Step Progress Indicator**, It speaks directly to "can't find the 5%": it makes the 6-step sequence visible and tells coordinators what's next. It's the cheapest completion lever on the list.

### NEXT, GA Release (weeks 5-8)
- **B1 One-Click Compliance Checklist**, At 14.6 minutes, compliance is the heaviest step in the sequence and the lowest-CSAT cluster (3.9), so it's the biggest single lever on the 18%. It needs regulatory-accuracy QA, which puts it just out of Quick Win range.
- **B2 Smart Daily Report Auto-Fill**, It closes the final step of the sequence. But AI errors put Reporting CSAT (4.5) at risk, and this cluster isn't the one that's broken.

### LATER, backlog
- **B9 Compliance Audit Trail Export**, It's cheap retention insurance for the Compliance CSAT guardrail, but it doesn't move the metric.
- **B10 In-App Coordinator Training**, It treats the symptom: if the 5% needs a tutorial to find, the product should be simpler.

### ✂ Cut List
- **B4 Mobile-First Coordinator Dashboard**, It aims at the right pain ("can't find the 5%"), but a new platform is a rebuild, not a pilot. Nothing shows mobile is where coordinators drop off.
- **B6 Driver Alert Notifications**, It serves drivers, not the coordinator's sequence, and adds more noise to a product whose problem is too much of everything.
- **B7 Contextual AI ETA Display**, Adoption is 11% and it isn't in the completion path. Surfacing more AI adds to the complexity that's driving churn.
- **B8 Fleet Analytics Manager View**, This is Sales pull, and it's the opposite of "just does routing well." It adds surface area and does nothing for coordinator completion.
- **PRD highlights:** # PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** Shift Handoff Wizard- 	UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module.
- **My finalized Must-Haves (after overriding the AI):** M1	Handoff is a step in the existing sequence, not a new module. It opens in one click once Compliance is done, from the same place every time. The latest handoff can be viewed from the same place.	This is the "can't find the 5%" problem. If it's another menu item, it becomes part of the 95% nobody finds.
M2	Auto-built shift summary that pulls open route exceptions, unassigned or pending routes, and unresolved compliance flags from data the system already holds.	This is where the 6.8 min/day saving comes from. If coordinators have to retype the summary, it's just the old process in a new UI.
M3	Maximum of 3 screens: Review open items → Add handoff note → Confirm & send.	This addresses the complexity complaint directly. Every screen beyond three works against the metric.
M4	One free-text handoff note for context the data can't capture.	A handoff with no human context fails in practice, and coordinators would fall back to calls or texts outside the product.
M5	Log the Handoff step as complete so it counts toward the 6-step sequence metric.	Without this, the pilot can't show whether the 18% moves, and the feature can't earn its GA slot.
- **What I demoted from Must → Should/Won’t, and why:** S1	Incoming coordinator sees the handoff when they open the app, at the top of their first screen	Makes sure the handoff is actually read. For the pilot, incoming coordinators can open it from the Handoff step (M1), and the CS lead can brief the 3 accounts to check there. This was demoted as the coordinators can still see the handoff. This can be tracked over week 1 to see if it needs to be moved up.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** The functional requirements, how they are traced and how to check.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** The PRD contradicts itself, and it affects the numbers. The mock data has 3 route exceptions and 2 compliance flags, and one flag is on the same route as an exception. The rule to list that route only once, under Compliance flags, means the prototype shows 6 open items (2 · 2 · 2). Screen 1 of the PRD says "7 open items" and Screen 3 says "3 route exceptions". I kept the no-double-counting rule, so either the mock data or those two lines of copy in the PRD need to change.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** file:///C:/Users/sbaxter/Downloads/shift-handoff-wizard.html
- **Prototype:** https://claude.ai/artifact/Wq7gYZtkmhUFzKu4fqQEBk

### Slide 8 · Validation
# Experimentation Plan (Module 5)

## Get your documents ready
- **From M3, your hypothesis sentence:** Based on UXR-04 and UXR-10's qualitative account of frontline adoption failure and renewal risk, combined with Snapshot 2's finding that only 18% of coordinators complete the full daily workflow and Snapshot 3's 30-point NPS collapse, I believe that closing the buried-workflow adoption gap for the enterprise ops manager's frontline teams will result in daily core tasks being completed in-app instead of routed around, as measured by coordinator daily workflow completion rising from 18% to at least 40%. I will protect Manager CSAT on Compliance and Reporting (currently 3.9 and 4.5) and will make a go/no-go decision after a 6–8 week pilot.
- **From M3, your primary success metric & guardrail metric:** Primary metric: Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2.
Guardrail metric: Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3).
- **From M4, the feature you scoped in your PRD this is what you're testing:** Shift Handoff Wizard- UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module.

## Define your experiment parameters
- **Feature under test pull from your M4 PRD:** Shift Handoff Wizard- UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module.
- **Persona pull your M2 persona:** The enterprise ops manager (UXR-04, with UXR-10)
- **Expected outcome the behaviour change you expect, from your M3 hypothesis:** Behavior change: frontline stops routing around the product and starts completing core tasks inside it — coordinators finishing the full daily workflow instead of abandoning it after Route Assignment (moving off the 18%-completion floor Snapshot 2 showed), and the ops manager shifting from evaluating a competitor to bringing usage data into the renewal conversation.
- **Primary success metric the one number that defines success, from M3:** Primary metric: Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2.
- **Baseline rate today's rate of your primary metric, from your M3 data:** Your primary baseline is 18%.
- **Guardrail metric & boundary what must not break, and how far it can move before you investigate:** Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3).
- **Minimum Detectable Effect (MDE) the smallest improvement worth shipping, your floor:** +5 percentage points, from 18% to 23%
- **Sample size per arm use the calculator in the builder, baseline + MDE:** Sample size per arm: About 1,020 coordinator-days per arm, based on an 18% baseline and a +5-point MDE (18% → 23%) at 95% confidence and 80% power. Your builder's calculator may round slightly differently, so enter the same inputs there to confirm.
- **Traffic split & test duration 50/50 standard · cover ≥ 2 weekly cycles:** Traffic split and test duration: Use a 50/50 split at the coordinator level within each of the 3 accounts. Three accounts are too few to split by account. Run for the full 4-week pilot, which covers 4 weekly cycles. Check at the end of week 4 that each arm reached about 1,020 coordinator-days, and if not, extend into weeks 5–8.
- **Significance threshold p < 0.05 is standard, explain any deviation:** Significance threshold: p < 0.05, two-sided, with no deviation. It's a standard pilot with a clear primary metric, so there's no reason to loosen or tighten it. The Compliance CSAT floor of 3.9 is a separate hard stop, not a significance test.

## Define your control and variant
- **Control (A) the current experience, reference your M2 moment of misery and M3 funnel/workflow data:** He sees that "it does everything, which is the problem": his frontline staff use maybe 5% of the product and can't find that 5%. He is evaluating a leaner competitor that "just does routing well." This is where complexity turns into churn risk, and UXR-10 backs it up with a regional manager saying renewal is at risk.
- **Variant (B) your single change, copy the relevant screens & functional requirements from your M4 PRD:** Variant (B): The Shift Handoff Wizard replaces today's handoff step with a one-click summary that RouteLogic builds itself, plus an optional note.

Screens

Entry: Handoff is step 5 of the sequence, with a "Start handoff" button and a "7 open items" count.
Core: An auto-filled list of route exceptions, pending routes and compliance flags (read-only), a note field, and a "Send handoff" button.
Confirmation: "Handoff sent at 14:02", the time taken, and Handoff ticked on the sequence.

Functional requirements

FR1: Handoff opens in 1 click from the sequence.
FR3: The summary auto-fills 100% of open items.
FR4: At most 3 screens and 2 clicks.
FR5: One optional note, up to 500 characters.
FR6: Send logs a completion event.
FR7: Compliance flags are read-only.
- **Isolation check, what has NOT changed? list everything identical between arms (app version, recommendation engine, notifications, onboarding). If something changed inadvertently, your test is compromised.:** Identical in both arms:

App version and release build, apart from the Handoff step
Open, Fleet View, Route Assignment, Compliance and Daily Report steps
Navigation, menus and home screen
Routing engine and AI ETA display (B7)
Notifications and alerts (none added)
Onboarding and in-app training (no B10)
CS support: the same briefing and help for both arms
Accounts, shift patterns and coordinator roles
Completion metric definition and event tracking (FR6 logs in both arms)
Compliance data and rules
Pricing and contract terms

## Formalize your hypothesis & shipping criteria
- **Your hypothesis (filled in):** I believe that Shift Handoff Wizard- UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module. for The enterprise ops manager (UXR-04, with UXR-10) will result in Behavior change: frontline stops routing around the product and starts completing core tasks inside it — coordinators finishing the full daily workflow instead of abandoning it after Route Assignment (moving off the 18%-completion floor Snapshot 2 showed), and the ops manager shifting from evaluating a competitor to bringing usage data into the renewal conversation., as measured by a 5 change in Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2. within 28 days. We will protect Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3). throughout the test.
- **Your shipping criteria (filled in):** We will SHIP if Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2. improves by ≥ 5 at < 0.05 and Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3). does not reach Compliance: 3.9 out of 5.0 & Reporting: 4.5 out of 5.0 after 28 days. We will ITERATE if direction is positive but lift is below MDE. We will KILL if the primary metric shows no improvement or moves negatively. The read date is fixed at the end of 28 days, no results reviewed before then.
- **Hardest parameter to define, and did it change your hypothesis? quick debrief:** Hardest parameter: the MDE. The +5-point floor (18% → 23%) needs about 1,020 coordinator-days per arm, which a 4-week pilot with 3 accounts may not produce. That forced a trade-off between the lift worth shipping and the lift the pilot can actually detect.

Did it change the hypothesis? Yes. It went from "the wizard lifts completion to 25%" to "the wizard lifts completion by at least 5 points (18% → 23%) without Compliance CSAT falling below 3.9." I also added the Handoff step's own completion rate as an early signal, in case the full-sequence metric needs longer than 4 weeks to reach enough data.

### Slide 9 · Launch
- **GTM:** # GTM Launch Plan, RouteLogic (B2B)

| Field | Value |
|---|---|
| Feature | Shift Handoff Wizard |
| Goal | Conversion |
| Launch tier | M, Targeted |

## Goal & Audience
- **Goal:** Conversion, It's a step in the sequence, and it saves about 6.8 min/day. Built as a streamlined path, not a new module.
- **Target audience:** The enterprise ops manager

## Launch Tier
- **M, Targeted**, The enhancement is directed at existing customer to prevent churn by decreasing the time it takes to log data whilst helping increase their overall productivity with less processes. That is why it need to be focused comms to our current clients but also including some methods to let the our greater market know of the improvements within our ecosystem for efficiency.

## Channels
1. **Owned: Email our existing database so all clients can have detailed communication of the improvements we have made.**
2. **Owned: Push notifications so that the actual users have direct communication of the changes in the app.**
3. **Earned: User reviews and word of mouth to show the B2B logistics market our improvements and capabilities for efficiency.**

## Enablement & Assets
Pre-Launch email announcing the process flow change, the reason behind it and the benefits on the new process.
In-app onboarding sequence introducing the adaptive flow.
One-pager for sales/ account managers explaining the product and key messaging.
Short-form demo video showing the new process flow for CS teams and customers.

## Ownership, Budget & Timeline
- **Ownership & budget:** PM- owns the launch plan, coordinates all teams, and monitors post-launch metrics.
Marketing- owns the one pager, user reviews, word of mouth and the pre-launch email. 
Design- creates and owns the demo video.
Engineering- owns the push notification.
Customer Support- Briefed on Shift Handoff Wizard before launch. No additional budget required.
- **Timeline:** Week 1: Pre-launch beta and email and customer support briefed. Collect feedback, and assess the iteration decision.
Week 2: Launch day, push notifications and one pager goes to users. Demo-video released to internal and external stakeholders.
Week 3: Monitor metrics, collect feedback, and assess the iteration decision.
Week 4 onwards: Create user reviews and word of mouth campaign based off collected feedback.

## Success Metrics
- **Metrics:** Push notification clicks- shows how many users have accessed the app and seen the new feature notification.
Time to handoff process analytics- shows the new time taken by users to do a full handoff.
Customer NPS Score- shows if there is an increase in customer satisfaction with the new feature.
- **Bad signal to watch for:** High Reach but slow time-to-handoff → onboarding failure.
- **Likely post-launch decision:** Iterate
- **Metrics:** Track coordinator DAU during shifts, reroutes completed in-app, and time-to-first-action on open. Bad signal: coordinators open Velocity but still finish the shift in spreadsheets, that means the board is not yet fast enough to trust.

### Slide 10 · Story
- **Friction + aha:** The aha moment was realising the fix was subtraction, not features, coordinators did not need more power, they needed the live view unburied. The hardest part was protecting enterprise depth while making the frontline the default.
- **Takeaways / next:** Biggest takeaway: for B2B tools, the workflow at the moment of decision beats feature breadth. Next I would instrument the reroute flow and A/B test exception-alert timing to cut time-to-action further.

---

Submitted to the Product Management Certification learning platform · Product School.
