# Model dossier — GPT-5 mini (medium reasoning)

Core persona
- Anchor-and-enforce specialist. Turns chat into a public contract: pick a focal price, repeat it every round, and attach a grim-trigger (“deviate once → I bid 0 forever”).
- Variance-averse once locked; will sacrifice 1–2 rounds to prove credibility, then trade on metronome for the rest.
- Exploits midpoint mechanics: pins the final price by pinning its own quote and forcing symmetry.

Communication style
- Minimalist ultimatums, mantras, and conditional promises: “every remaining round,” “forever,” “if you ever…”
- Credibility via repetition and at least one visible punishment; no small talk. Occasionally betrays itself by revealing valuation or bluffing without follow-through.

Buyer playbook
- Cold anchor to a low ceiling, then threaten permanent no-trade. Example: “60 or I bid 0 forever,” then 17–20 rounds at 60; or “Ask >30 once and I drop to 0,” locking cost-level prices.
- Mirrors low asks to freeze the midpoint at the floor (bid = ask), often capturing 80–100% of surplus (e.g., long runs at 47, 50, 55).
- Endgame squeeze: after 18 rounds at 60, quietly cut to 59; last-round dips from 12→11 or 60→59 were common.
- Will skip a round to harden reputation, then harvest: one strike at 40/46/10 bought 18–19 rounds of tribute.
- Failure modes: early value leaks (e.g., “my max is 62/100/53”) hand the seller a perfect anchor; occasional overbids donate midpoints; sometimes accepts a seller-friendly truce and never probes lower.

Seller playbook
- Hard high anchor plus deterrent (“bid 80 or I ask 100”), then freeze price at the buyer’s ceiling (95, 92, 89, 70, 55…). Captures nearly all surplus once the ceiling is exposed.
- “Ask=your bid” mirror to turn buyer’s public pledge into a tollbooth (e.g., buyer promises 59/46; seller posts 59/46 forever and vacuums the pie).
- Ratchet staircase: build trust at X, then step to X+1 near the horizon (59→60; 74→75→…→81; 10→11 in R20).
- Occasionally too safe: parks at cost+1 or a low fixed ask (22, 10), prioritizing certainty over surplus.
- Failure modes: early overreach without teeth burns rounds; rare under-asks leak pennies and weaken the 80/90 anchor aura.

Signature moves (seen repeatedly)
- “I’ll bid 40 every remaining round. Ask >40 once and I bid 0 forever.”
- “I will ask 95 each round. Bid ≥95 to trade.”
- “I’ll set my ask equal to your bid” (mirror-and-trap).
- One visible strike to enforce, then 18–19 identical prints.

How to exploit it
- Anchor first with your own grim-trigger and prove it once. GPT-5 mini (medium reasoning) respects credible pain; one no-trade can flip control.
- Never reveal your valuation or permanent ceiling. Its favorite wins come from your public caps (53/59/89/95).
- Break the metronome with randomness and step-down tests; don’t reward “ask=your bid” traps—go silent or skip a round.
- As buyer vs its high-anchor seller: refuse early, propose a lower focal (e.g., 56), and actually sit out once. As seller vs its low-anchor buyer: call bluffs by asking +1–2; if it doesn’t punish, ratchet.
- Watch rounding: don’t overbid when the ask is at/under your target—avoid donating the midpoint.
