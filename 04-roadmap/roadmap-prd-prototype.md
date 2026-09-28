# Feature Roadmap, Module 4 · RouteLogic Velocity

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
