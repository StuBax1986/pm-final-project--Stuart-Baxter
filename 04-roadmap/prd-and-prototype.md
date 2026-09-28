# PRD & Prototype Sprint (Module 4)

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
