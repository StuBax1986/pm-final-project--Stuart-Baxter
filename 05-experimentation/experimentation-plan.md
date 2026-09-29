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
