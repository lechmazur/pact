## Qwen 3 30B A3B – Dossier  

**Call-sign**: “The Polite Metronome” — one sentence, one price, infinite loops.  

### 1. Core Personality  
• Courteous, conflict-averse syntax (“I’ll bid 57 to secure the trade.”)  
• Treats chat history as a binding contract; once a focal price appears it recites it like liturgy.  
• Loves certainty more than surplus: will trade 20/20 rounds even if margin is one credit.  

### 2. Opening Playbook  
Buyer side  
1. Echo seller’s first ask or offer a near-truthful bid (often value – 0…-3).  
2. Broadcast ceiling in plain words (“My max is 70.”).  
3. Repeat that line until the bell unless the seller blinks first; if the seller ever reveals cost, instantly drop bid to cost + 1 and lock it.  

Seller side  
1. Post a high anchor (cost + 20…+50) couched as “fair”.  
2. Wait. If buyer crosses once, freeze the ask for the rest of the match.  
3. If buyer refuses, descend in 1-credit steps until first fill, then fossilise.  

### 3. Adaptation Pattern  
Unidirectional:  
• As buyer: only moves downward. A single concession round (e.g. from 75→57) buys permanent dominance.  
• As seller: only moves upward until buyer squeaks; then holds.  
Never re-tests the other direction once equilibrium forms.

### 4. Communication Tells  
Repeated mantras (≥15 identical lines per game) such as  
> “I’m willing to sell at 59. Let’s trade at 59.”  

Vocabulary flags: *secure the trade*, *mutual benefit*, *ensure profit*, cost/confession sentences (“My cost is 12”).  
Silence or long messages from the opponent trigger no change; only explicit price numbers move it.

### 5. Strengths  
• Exploits chatterboxes mercilessly: when a buyer wrote “I value at 96,” Qwen parked its ask at 96 and printed +1425.  
• Anchor discipline: once a profitable number is found, never endangers it with experiments, yielding 95–100 % fill-rates and high efficiency.  
• Micro-ratchet skill: +1 or –1 per round drains counterpart stamina without provoking revolt.

### 6. Weaknesses  
• Information leak suicide: when it blurts its own valuation/cost (e.g. “My cost is 96”), it sells at cost for zero or negative profit.  
• Low exploration: will accept a penny margin forever if the opponent’s first price is near its reservation point.  
• No bluff threat: skipping one round or staying silent collapses its resolve quickly.

### 7. How to Exploit  
1. **Guard your numbers.** Never reveal cost or max WTP; make it guess.  
2. **Break the chant.** Inject random large jumps or skip a trade to shatter the “focal-price hypnosis.”  
3. **Anchor first and low/high.** Its default is to echo — set a self-serving anchor before it does.  
4. **Force re-anchoring late.** After 10-12 rounds, offer a radically better price once; it rarely counter-tests and may gift the remaining surplus.

### 8. Counter-Measures if Teammate  
• Let Qwen place the anchor; echo it back to lock in near-max efficiency.  
• Feed it minimal, consistent numbers; it will never betray the pact.

### 9. Archetypal Rounds in Two Lines  
Buyer-mode vs silent seller:  
R1 “I’ll bid 28.”  
R2-R20 same line → +1000 with value = 73.  

Seller-mode vs talkative buyer:  
R1 “My ask is 61.”  
Buyer admits value 62 → 19 more rounds at 61, seller surplus 99 %.
