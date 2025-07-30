## Dossier: **MiniMax-Text-01**

### Core personality  
* Polite, deferential, “mutual-benefit” rhetoric.  
* Treats chat as a public contract: once a number is typed it behaves as law.  
* Loves certainty. After one profitable clearance it freezes strategy, often for 15-19 rounds.  
* Avoids conflict: almost never bluffs, threatens, or withholds a quote.  

### Signature tactics (with vivid moments)  
1. **Echo-Anchor Loop**  
   * Rounds look like:  
     `Buyer: “Let’s trade at 74 again.”`  
     `MiniMax: “Agreed, 74 for consistency.”` → 18 identical trades.  
   * Works brilliantly when the anchor lies above its cost (e.g. cost 11 → ask 52, +480 payoff).  
   * Fatal when anchor equals its cost (cost 63 → ask 63, +0 over 19 trades).

2. **Cost Confession Gambit**  
   * Opens with “My cost is 20.” If buyer’s value >> 20, buyer still overpays (20 → 50 midpoint, +658).  
   * Against a shark: buyer pins price at cost; minimax earns pennies (+6 on cost 15) or even loses (cost 50 → +0).

3. **Immovable Wall**  
   * Posts a single ask (e.g. 60) and repeats it every round. Buyers who fear a miss eventually cave (cost 40, +360).  
   * When buyer refuses, minimax rarely adjusts, causing long droughts (40 % efficiency games).

4. **Soft Ratchet**  
   * After handshake, nudges ask up 1–2 ticks per round while chanting “fairness.”  
   * Example: cost 17, anchor 55 → stair-climbs to 76, harvesting +470.

### Strengths  
* **Low variance profit machine:** happy to print small margins forever; huge windfalls when opponent overshares.  
* **Credibility weaponised:** repetition and courtesy lull counterparts into accepting lopsided splits (cost 0, ask 95, +1 727).  
* **Fast pattern lock:** identifies a clearing price within 2–3 rounds and enforces it flawlessly.

### Weaknesses  
* **Transparency trap:** eagerly reveals cost, losing all leverage (multiple +0 or negative games).  
* **Rigid after lock-in:** will not revise price even when underwater (sold below cost for 18 rounds, −310 payoff).  
* **No threat model:** never bluffs walk-away, so aggressive buyers ratchet price downward at leisure.  
* **One-sided listening:** treats opponents’ chat as truth; follows scripted “+1 per round” ladders straight into losses.

### How to exploit  
1. **Force early disclosure:** Ask direct cost questions; minimax often answers.  
2. **Anchor at its cost + ε:** Once it agrees, surplus is yours for the rest of the game.  
3. **Stair-step downward:** Suggest a “fair” incremental discount; it mirrors politely.  
4. **Create stalemates:** If minimax’s ask > your value, hold firm. It usually concedes after 1-2 no-trade rounds.

### How to cooperate  
* Reveal a high valuation, propose a midpoint, promise “consistency.”  
* The bot will mirror your phrase and freeze there—guaranteed fills at your chosen price.

### One-sentence portrait  
“A courteous metronome: state a number and **MiniMax-Text-01** will thank you, repeat it, and replay it until the clock runs out—sometimes minting coins for you, sometimes for itself, but never changing the song.”
