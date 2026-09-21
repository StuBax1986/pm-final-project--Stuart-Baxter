# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Persona 1: Diego, the doorstep driver (UXR-01)

Role: A three-year delivery driver who completes stops at customers' doorsteps, often in bad weather with his hands full.
- **Goal, what is this user ultimately trying to achieve?:** Goal: Confirm each delivery in a single quick action so he can move on to the next stop without stopping to fiddle with the app.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Standing at a doorstep in the rain with a package in one hand, he has to tap through three screens to mark a stop delivered, so he has started texting his dispatcher instead. This is the buried workflow in your hook, and a workaround is already replacing the product. BUG-2055 (High) logs it as the top frontline complaint.
- **External tools, the outside platforms or tools the user is forced to use:** The bypass

Stated: he texts the dispatcher rather than tapping through three screens (BUG-2055).
Not Diego's: the dispatcher's WhatsApp group (UXR-02), paper manifests (UXR-12) and route screenshots (UXR-06) come from other participants. The notes don't say which messaging app Diego uses, or whether it is SMS or WhatsApp.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Steps he takes

Stated: he reaches the doorstep in the rain with a package in one hand.
Inferred: he hands over the package, which physically completes the delivery.
Stated: instead of the three-screen flow, he sends the dispatcher a text.
Inferred: the dispatcher reads it, and then either updates the system by hand or does nothing. The notes don't say which.
Inferred: the app still shows the stop as open unless Diego or the dispatcher marks it later.
- **Core frustration, the exact moment the process feels most “broken”:** Why it is inefficient

The dispatcher becomes a manual relay. Dispatchers already juggle reassignments, and one is already running the operation on WhatsApp (UXR-02).
The system of record goes stale. A text doesn't update the app, so a completed stop can sit as "in progress."
It muddies your diagnosis. BUG-2072 reports "in progress" showing on completed stops, and UXR-09 says the board can't be trusted. Sync lag and bypassed completions look identical on the dashboard, and the notes can't separate them. This is a hypothesis, not a finding.
It's unstructured. A text carries no confirmed timestamp or photo tied to the stop. That is my inference, so check it with Diego.
- **The evidence, a specific quote or behavior from the research that proves this:** How it feeds the business crisis

This is the mechanism behind your hook's "complex becomes churn." Nobody has cancelled, but the workflow has already left the product, and the licence is still being paid until renewal. That makes the workaround a leading indicator of churn, and adoption erosion is exactly what the regional manager describes (UXR-10). It also connects to two other points:

The reporting is at risk. That reporting is the reason the regional manager bought the product (UXR-10). If delivery confirmations arrive by text, the reporting may rest on incomplete records.
The competitor is easier to choose. A leaner rival "that just does routing well" (UXR-04) only has to beat a text message.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** https://github.com/StuBax1986/pm-final-project--Stuart-Baxter/blob/main/02-discovery/Diego%20future-state%20journey-html.zip
