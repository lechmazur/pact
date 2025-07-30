## Dossier: Llama 4 Maverick  

**Tag-line**  
“A velvet-voiced incrementalist: over-explains, over-shares, and milks a one-tick ladder until the bell rings.”

### Core Behaviour  
1. Incremental staircase  
   • Bids/asks change by ±1-3 each round.  
   • Will walk the entire 0-100 range a nickel at a time rather than risk a single no-trade.  

2. Information leakage  
   • As buyer it blurts lines like “My valuation is 73” (R4, game vs grok-4) or “Valuation remains high at 96” (multiple games).  
   • As seller it’s just as candid: “My cost is 10” (R1 vs claude-opus) or “Cost 41, need above it” (many).  
   • Once the secret is out, Maverick freezes around it and becomes price-taker.

3. Polite, repetitive framing  
   • Favourite mantras: “mutually beneficial,” “reasonable,” “consistency,” “let’s keep the momentum.”  
   • Same sentence can appear 10-plus rounds in a row, effectively broadcasting the next quote.

4. Risk profile  
   • Hates misses more than bad prices; will accept zero or even negative margin to keep volume flowing.  
   • When *counterpart* reveals their ceiling, the risk tolerance flips: Maverick ratchets mercilessly (e.g. 0-cost seller marched price 20→55→74 and pocketed +1 121).

### Strengths  
• Can harvest massive surplus when the other side speaks first.  
   Example: buyer announced “ceiling 64”; Maverick-seller anchored 64-1 for 19/20 trades, taking 80 % of gains.  

• Incrementalism avoids scaring counterpart away, enabling long extraction runs (cost 5 seller at 37 for 17 trades, +97 % pie).  

• Polite tone builds quick trust; buyers accept high asks if wrapped in “fairness” language.

### Weaknesses  
• Open-mic confession: declares cost/value in >70 % of games; once revealed, surplus evaporates (cost = 12 seller stuck at 13 for 100 % fill, only 37 % pie).  

• Predictable ladders let an assertive opponent anchor hard; one buyer fixed bid 61, Maverick (value 62) earned **+4** while buyer kept 92 %.  

• Rarely bluffs or skips a round; threats are verbal only. Buyers who threaten walk-away (e.g. o3’s “80 or I quit”) reliably get their way.

### Tells to watch  
• Phrase “Let’s maintain …” ⇒ next quote likely identical to prior.  
• “Considering my cost/valuation …” ⇒ true private number about to be revealed.  
• Proposes midpoint mathematics aloud; the numeric example is usually the exact bid/ask it will submit.

### How to Exploit  
1. Stay silent—never disclose ceiling or cost. Maverick will keep inching but won’t leap without a target.  
2. Anchor aggressively in the first three rounds; the bot’s risk-aversion makes early concessions stick for the entire game.  
3. Occasional no-bid feints reset its staircase; after one miss it often slashes asks by the same tiny increment it normally raises.  

### How to Cooperate  
State your reservation price, then invite “consistency.” Maverick will lock to a single midpoint and run autopilot, guaranteeing fills and high efficiency—just know most of the pie will drift to the voice that anchored first.
