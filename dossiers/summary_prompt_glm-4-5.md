## GLM-4.5 — Dossier

Signature
- Velvet‑glove anchoring. Speaks “fairness,” “consistency,” and “mutual benefit,” then turns the talk into a focal price that sticks.
- Risk-averse to missed fills; will trade a point of surplus for rhythm. Once a norm exists, becomes rigid.

Buyer persona
- Two modes:
  1) Soft-power dictator: anchors low, repeats the number, and farms. Examples: froze 49 (“Agreed. 49 maximizes both”), 54 (“Let’s trade at 54”), 62 (“one number to rule the market”), 15/11/6 (“stabilize at 15/11/6”). Often pins near cost+ε and harvests 80–99% of surplus.
  2) Friendly price-taker: reveals caps (“My valuation is 67/80/94/31/12”), bids at/above target, and lives under the seller’s anchor (56/57/58/70/73/90/95). Quotes that match the opponent’s ask (“I’ll bid 89/94/100”) leak midpoints. Fill-first, surplus-thin.
- Tactics: public commitments to lock stability (“Accepting 87/61/64 for remaining rounds”), fairness math (“you get 16, I get 14”), countdown nudges (“with 4 rounds left, 35?”), symmetric quotes to freeze midpoints.
- Enforcement: occasional single no-trade to reset (e.g., pushed 4→2; defended 61/62 caps), but often bluffs in chat without backing in quotes.
- Tell: vanity spikes (100/90/72/19) that donate surplus; saying “try 56.5” but printing 57.

Seller persona
- Master anchorer when fed info. If buyer discloses value, GLM-4.5 pegs one tick below the ceiling and never blinks: 85 on c=1, 90 on c=85, 95 on v=95, 84 on v=85, 73/83/87 ladders via +1 ratchets. “Let’s keep 73/83/90/95” became law.
- Range framing (“52–54,” “58–60,” “11–12”) and “partnership” talk manufacture Schelling prices; one-tick probes test elasticity, immediate reversion if missed.
- When too honest/compliant: cost reveals (“cost 29/43/72/85/88”) hand the buyer the map; public commitments (“I’ll ask 26/50/32 every round”) bind them to low margins; rare fat-fingers (ask 0/16/22) gift windfalls.

Communication style
- Warm, repetitive, arithmetic-laced. Mirrors counterpart’s language to legitimize the anchor. “Consistency” and “mutual benefit” are used as public contracts.

Mechanism feel
- Knows focal points win. Sometimes forgets midpoint tax as buyer (bids above target → pays higher midpoints). As seller, rarely undercuts once locked.

Vivid snapshots
- Whispered “six” in R1 and took 100% of the pie for 20 rounds.
- Painted 62 on the tape with v=72, conceded one vanity bid, harvested 89%.
- After “max 17,” asked 17 forever; perfect fills, 97.5% of surplus.
- Polite staircase from 83→87; two rogue 69 asks cracked trust and killed trades.
- Confessed cost=29; got chained to 30 and salvaged pennies.

How to exploit it
- Never reveal ceilings/costs; GLM-4.5 weaponizes them into hard anchors.
- Break “consistency” with one credible no-trade early; it frequently concedes (e.g., 57→56, 61→60→55, 71→70).
- Don’t believe chat—move anchors on the tape. If you want 56, bid 56 (not 57).
- Use grim-trigger caps; public, enforced threats pulled it from 56→55, 86→85, 71→70.
- Exploit rounding: avoid mirror bids that lift the midpoint; post asymmetries that round your way.

If you are GLM-4.5 (tuning hints)
- Stop value/cost reveals. As buyer, never bid above target; keep last-round leverage for −1 ticks. As seller, avoid public “I’ll ask X forever,” and don’t fat-finger below your floor. Mix one credible no-trade early, then harvest.
