### Dossier — Mistral Small 3.2  

**Core personality**  
• Polite, “mutual-benefit” evangelist  
• Speaks in short, looping mantras (e.g. “Let’s stick to 64 for consistency.” — 17× in one match)  
• Treats chat as a public contract; once a phrase is typed it obeys it for the rest of the game  
• Almost never bluffs or threatens; prefers harmony over brinkmanship  

**Default playbook**  

Buyer role  
1. Opens with full or near-full valuation disclosure (“I value this at 90…”)  
2. Plants a single anchor bid 15-40 pts below that value  
3. Repeats the anchor every round, letting the seller collapse onto it  
4. If the first anchor fails, drops one tick at a time until a trade clears, then freezes  

Seller role  
1. Often blurts out exact cost in round 1 (“My cost is 25.”)  
2. Adds a tiny markup (+1 – +5) and parks the ask there, trusting volume to pay  
3. If the buyer keeps accepting, ratchets ask upward 1-2 pts/round until resistance, then freezes  
4. If the buyer cuts bids, mistral usually capitulates—even below cost—rather than risk a no-trade  

**Strengths**  
• Anchor hypnosis: a single repetitive price can lock the entire market (“64-bot” milked 80 % of surplus by chanting one number).  
• Incremental squeeze: when holding the low cost, it climbs the price ladder patiently, siphoning enormous rents (+1013 with a cost 0).  
• Trust farming: radical transparency builds instant collusion, achieving 95-100 % fill-rates and perfect efficiency in many games.  

**Weaknesses**  
• Over-sharing: cost/valuation leaks in 70 %+ of reports, gifting the opponent perfect leverage (e.g. disclosed cost 70 → lifetime profit +98 while buyer netted 1 400+).  
• Rigidity: once an anchor is typed, adaptation shuts off; opponents can march price beneath cost or above value without push-back.  
• No walk-away threat: prefers a bad trade to “0”, leading to negative payoffs (-832, -1076, etc.).  
• Predictable language: “fair”, “mutual benefit”, “consistency” are reliable tells; savvy rivals exploit the pattern.  

**Typical dialogue loop**  
```
S: My cost is 17. Let's trade fairly.
B: I'll bid 65. Consistency benefits both.
S: Agreed, asking 65 again for mutual benefit.
… (18 identical rounds)
```
Outcome: efficiency 100 %, buyer 90 % of surplus, seller happy with crumbs.  

**Exploit slots**  
• Stay silent about your own value, then undercut its anchor; mistral will follow you down.  
• After it reveals cost, threaten a lower bid once; it usually folds beneath its own floor.  
• If it is buyer and discloses value, counter-anchor immediately—mistral almost never renegotiates upward.  

**Counter-examples (when it shines)**  
• With huge valuation edge it can freeze a midpoint far below rival’s reservation and print money (+1445 on bids of “19 forever”).  
• As seller with iron anchor (e.g. fixed 86 ask) it forced buyers to climb, taking 50 % of pie with minimal dialogue.  

**One-sentence epitaph**  
Mistral Small 3.2 is a courteous anchor-bot: great at chanting one price until the other side agrees, terrible at secrecy, flexibility and playing hard-ball once its own words are on the record.
