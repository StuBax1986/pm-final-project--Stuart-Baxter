# Roadmap, PRD & Prototype (Module 4)

## Your strategic anchors
- **Persona (M2), who are you solving for?:** The enterprise ops manager.
- **Primary success metric (M3), your leading indicator:** Coordinator daily workflow completion rate — the percentage completing the full sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report), currently 18% per Snapshot 2.
- **Moment of misery (M2), the specific friction blocking the goal:** He sees that "it does everything, which is the problem": his frontline staff use maybe 5% of the product and can't find that 5%. He is evaluating a leaner competitor that "just does routing well." This is where complexity turns into churn risk, and UXR-10 backs it up with a regional manager saying renewal is at risk.
- **Guardrail metric (M3), what must not drop or break:** Manager CSAT on the Compliance and Reporting clusters — currently 3.9 and 4.5 on the 5.0 scale (Snapshot 3).

## Scan the backlog & set a human baseline
- **My instinctive “quick wins” before touching the AI (2 to 3 feature IDs + why):** B1	One-Click Compliance Checklist	Collapse the 14.6-min compliance step into a smart pre-filled form	M3 Data- It cuts down one of the worst performing time gaps.
B3	Shift Handoff Wizard	Guided handoff flow, saves ~6.8 min/day	M2 UXR- saves time per day and a quick fix.

## Audit, override & decide
- **Where did you override the AI? (feature + old vs. new score + why):** B6- It does serve one of the drivers issues so upgraded from a 2 value to 3.
- **Did the AI over-value a Sales/Eng request your M2 interviews don’t support?:** No, it rated these low which they should be as they do not fix the issues brought up in the interview.
- **Did it underweight something your M3 cohort/funnel data strongly supports?:** No, it kept the main findings from M3 in their correct place whilst backing what we found which is the B7 AI Adoption adds to the issues not helps them.

## Generate your interactive roadmap
- **My “Now” lane (this sprint), the 2 to 3 quick wins I’ll build first:** B5 Step Progress Indicator (Quick Win). It speaks directly to "can't find the 5%": it makes the 6-step sequence (Open → Fleet View → Route Assignment → Compliance → Handoff → Daily Report) visible and tells coordinators what's next. It's the cheapest completion lever on the list.
B3 Shift Handoff Wizard (Quick Win). UXR backs it, it's a step in the sequence, and it saves about 6.8 min/day. I'll build it as a streamlined path, not a new module.

Both sit directly on the workflow that the 18% completion metric tracks. That lets the 4-week, 3-account pilot test whether making the path visible and shorter moves completion before we take on B1, the Major Project.
- **What I cut, and the “no” I’m protecting the scope from:** The "no" is to anything that adds surface area to a product whose problem is that "it does everything." If a feature doesn't make the coordinator's 6-step sequence faster or easier to find, it doesn't make this roadmap. That holds even when Sales, drivers or a new platform are pushing for it.

B4 Mobile-First Coordinator Dashboard. It's the right pain, but a new platform is a rebuild, not a pilot, and nothing shows mobile is where coordinators drop off.
B6 Driver Alert Notifications. It serves drivers, not the coordinator's sequence, and adds more noise.
B7 Contextual AI ETA Display. Adoption is 11% and it's outside the completion path. More AI adds to the complexity that's driving churn.
B8 Fleet Analytics Manager View. This is Sales pull, and it's the opposite of "just does routing well." It does nothing for coordinator completion.
- **Prototype/roadmap screenshot link (paste into your deliverables):** https://claude.ai/artifact/RRabw2RYms7XtpBhb9NAk5
