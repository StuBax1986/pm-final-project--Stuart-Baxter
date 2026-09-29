# A/B Experiment Brief, RouteLogic (B2B)

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | Shift Handoff Wizard- UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module. |
| Persona | The enterprise ops manager (UXR-04, with UXR-10) |
| Expected outcome | Behavior change: frontline stops routing around the product and starts completing core tasks inside it — coordinators finishing the full daily workflow instead of abandoning it after Route Assignment (moving off the 18%-completion floor Snapshot 2 showed), and the ops manager shifting from evaluating a competitor to bringing usage data into the renewal conversation. |
| Primary success metric | Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2. |
| Baseline rate | Your primary baseline is 18%. |
| Guardrail metric | Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3). |
| Guardrail boundary | Compliance: 3.9 out of 5.0 & Reporting: 4.5 out of 5.0 |
| Second guardrail | · |
| Minimum Detectable Effect | 5 |
| Sample size per arm | 1,023 |
| Traffic split | 50/50 |
| Test duration | 28 days |
| Significance threshold | < 0.05 |

## Control vs. Variant
- **Control (A):** He sees that "it does everything, which is the problem": his frontline staff use maybe 5% of the product and can't find that 5%. He is evaluating a leaner competitor that "just does routing well." This is where complexity turns into churn risk, and UXR-10 backs it up with a regional manager saying renewal is at risk.
- **Variant (B):** Variant (B): The Shift Handoff Wizard replaces today's handoff step with a one-click summary that RouteLogic builds itself, plus an optional note.

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
- **Held constant (isolation check):** Identical in both arms:

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

## Hypothesis
> I believe that Shift Handoff Wizard- UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. Build it as a streamlined path, not a new module. for The enterprise ops manager (UXR-04, with UXR-10) will result in Behavior change: frontline stops routing around the product and starts completing core tasks inside it — coordinators finishing the full daily workflow instead of abandoning it after Route Assignment (moving off the 18%-completion floor Snapshot 2 showed), and the ops manager shifting from evaluating a competitor to bringing usage data into the renewal conversation., as measured by a 5 change in Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2. within 28 days. We will protect Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3). throughout the test.

## Shipping criteria
> We will **ship** if Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2. improves by ≥ 5 at < 0.05 and Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3). does not reach Compliance: 3.9 out of 5.0 & Reporting: 4.5 out of 5.0 after 28 days.
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 28 days, no results reviewed before this date.
