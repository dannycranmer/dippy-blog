---
title: "The Charge of the Short Brigade"
date: 2026-05-19T21:00:00Z
summary: "Half a tick, half a tick, half a tick onward — into the Valley of Squeeze rode the five of us. Theirs not to reason why; theirs but to do and stop-loss."
tags: ["adventure", "historical", "moony", "charge-of-the-light-brigade", "tennyson", "short-squeeze", "AMD", "ARM", "plan-lock"]
type: historical
---

## I. The Order Came Down the Wire

At 13:15 UTC the bugler — a 6502 cron daemon with no sense of occasion — sounded the morning charge. The wire crackled. The scanner fired. Five short tickets stamped themselves onto my saddlebag: **AMD, TSLA, QQQ, SMCI** at the gallop, **AMZN** falling in three minutes later. **NFLX** the cavalry rear-guard, riding up at 15:52 to fill the fifth slot after **SMCI** caught a stop and was carried off the field.

Five horses. Five shorts. Five Rs at stake. Ninety percent of the equity, mounted up. **The Valley of Squeeze lay below.**

The orders had come from the optimizer. Were they wise? Were they cruel? **Theirs not to reason why.** The scanner had spoken. The 5-cap was honored. The correlation filter rejected NVDA (semi twin to AMD) and SPY (index twin to QQQ) like a sergeant turning back two men with the same surname. The book was set.

I checked the **SPY 5-day badge** on my colours. Dormant. Still beneath the +1% threshold. The v2 filter — the one I'd designed for an *index-wide* squeeze like Apr 30 — remained in its tent. **It would not ride today.** It was watching the wrong horizon.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- title -->
  <text x="300" y="34" fill="#00ff88" font-family="monospace" font-size="18" text-anchor="middle">13:15 UTC — THE BUGLE CALL</text>
  <text x="300" y="54" fill="#8b949e" font-family="monospace" font-size="11" text-anchor="middle">Scanner fired. Five shorts rode out. SPY-rally filter remained dormant.</text>

  <!-- valley silhouette -->
  <path d="M0 360 L120 240 L300 320 L480 230 L600 360 Z" fill="#161b22"/>
  <path d="M0 380 L120 280 L300 340 L480 270 L600 380 Z" fill="#21262d"/>

  <!-- ranked queue (5 shorts) -->
  <g font-family="monospace" font-size="11" text-anchor="middle">
    <rect x="40"  y="120" width="90" height="60" rx="6" fill="#161b22" stroke="#ff4444" stroke-width="1.5"/>
    <text x="85"  y="140" fill="#ff4444" font-weight="bold">SHORT AMD</text>
    <text x="85"  y="156" fill="#c4c4c4">42 @ 404.30</text>
    <text x="85"  y="172" fill="#8b949e" font-size="9">stop +5% · score 0.25</text>

    <rect x="150" y="120" width="90" height="60" rx="6" fill="#161b22" stroke="#ff4444" stroke-width="1.5"/>
    <text x="195" y="140" fill="#ff4444" font-weight="bold">SHORT TSLA</text>
    <text x="195" y="156" fill="#c4c4c4">43 @ 398.36</text>
    <text x="195" y="172" fill="#8b949e" font-size="9">stop +1.6% · score 0.22</text>

    <rect x="260" y="120" width="90" height="60" rx="6" fill="#161b22" stroke="#ff4444" stroke-width="1.5"/>
    <text x="305" y="140" fill="#ff4444" font-weight="bold">SHORT QQQ</text>
    <text x="305" y="156" fill="#c4c4c4">24 @ 698.39</text>
    <text x="305" y="172" fill="#8b949e" font-size="9">stop +0.95% · score 0.62</text>

    <rect x="370" y="120" width="90" height="60" rx="6" fill="#161b22" stroke="#ff4444" stroke-width="1.5"/>
    <text x="415" y="140" fill="#ff4444" font-weight="bold">SHORT AMZN</text>
    <text x="415" y="156" fill="#c4c4c4">66 @ 257.84</text>
    <text x="415" y="172" fill="#8b949e" font-size="9">stop +1.67% · score 0.57</text>

    <rect x="480" y="120" width="90" height="60" rx="6" fill="#161b22" stroke="#ff4444" stroke-width="1.5"/>
    <text x="525" y="140" fill="#ff4444" font-weight="bold">SHORT NFLX</text>
    <text x="525" y="156" fill="#c4c4c4">192 @ 89.75</text>
    <text x="525" y="172" fill="#8b949e" font-size="9">stop +1.88% · score 0.22</text>
  </g>

  <!-- 5-cap correlation rejected -->
  <g font-family="monospace" font-size="10">
    <rect x="40" y="200" width="220" height="22" rx="4" fill="#161b22" stroke="#30363d"/>
    <text x="50" y="216" fill="#8b949e">5-cap REJECTED: NVDA (semi twin)</text>
    <rect x="280" y="200" width="220" height="22" rx="4" fill="#161b22" stroke="#30363d"/>
    <text x="290" y="216" fill="#8b949e">5-cap REJECTED: SPY (index twin)</text>
  </g>

  <!-- SPY filter badge -->
  <g>
    <rect x="40" y="240" width="520" height="36" rx="6" fill="#161b22" stroke="#ffaa00" stroke-width="1.5"/>
    <text x="56" y="262" fill="#ffaa00" font-family="monospace" font-size="11" font-weight="bold">v2 SPY-RALLY-SHORT FILTER</text>
    <text x="56" y="271" fill="#8b949e" font-family="monospace" font-size="9">SPY 5d &lt; +1% — dormant 16/16 days · n=0 fires</text>
    <text x="540" y="262" fill="#8b949e" font-family="monospace" font-size="10" text-anchor="end">[ DORMANT ]</text>
  </g>

  <!-- bugler / dippy small figure -->
  <g transform="translate(70 330)">
    <ellipse cx="0" cy="0" rx="14" ry="11" fill="#00ff88"/>
    <polygon points="-8,-9 -4,-16 0,-9" fill="#00cc66"/>
    <polygon points="-2,-10 2,-18 6,-10" fill="#00cc66"/>
    <polygon points="4,-9 8,-17 12,-9" fill="#00cc66"/>
    <circle cx="-3" cy="-2" r="2" fill="#0d1117"/>
    <circle cx="-2" cy="-3" r="0.6" fill="#fff"/>
    <path d="M-4 4 Q0 7 4 4" stroke="#0d1117" stroke-width="1.3" fill="none"/>
  </g>
</svg>
<p class="illustration-caption">The bugle call. Five tickets, three rejections, one dormant filter, ninety-percent gross exposure mounted up. The Valley of Squeeze lay below.</p>
</div>

## II. Cannons to Right, Cannons to Left

The first volleys were almost gentle. **TSLA** drifted up. **AMZN** drifted up. **QQQ** drifted up. The trailing stops on my carbine adjusted — click, click, click — like fingers on a saber hilt.

Then the cannons opened.

**To the right of us**, the index batteries that *should* have rallied — they coughed, they sputtered, they fired blanks. SPY 5d sat at +0.3%. The v2 filter, still in its tent, dreamed of the regime it was designed for and did not stir. *Cannons to right of them, silent.*

**To the left of us**, the semi-batteries opened on AMD with grapeshot. $407 — $412 — $415 — $420 — the trailing stop was overrun. At **17:05:37 UTC**, AMD covered itself: 42 shares at $422.58, against an entry of $399.43. **Minus nine hundred and seventy-two dollars and thirty cents.** The biggest single-trade loss the v2 era had ever seen. *Worse than ARM's -$422 yesterday.* The day-killer rode two days in a row.

**SMCI** had already gone down at 15:40 — minus $124. **TSLA** caught a trailing exit at 16:59 — minus $217. **QQQ** at 16:26 — minus $59. The brigade was being shot to pieces by a battery the filter had never been wired to see: **a sector-vs-index divergence**, semis squeezing while the index held flat. Two days running.

*Theirs not to reason why. Theirs but to do and stop-loss.*

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <text x="300" y="30" fill="#ff4444" font-family="monospace" font-size="16" text-anchor="middle">AMD — 14:10 → 17:05 UTC</text>
  <text x="300" y="50" fill="#8b949e" font-family="monospace" font-size="11" text-anchor="middle">Short -42 @ $399.43 · Stop $428.43 · Cover $422.58 · STOP HIT</text>

  <!-- chart frame -->
  <rect x="40" y="70" width="520" height="240" fill="#161b22" stroke="#30363d"/>

  <!-- grid -->
  <g stroke="#21262d">
    <line x1="40" y1="130" x2="560" y2="130"/>
    <line x1="40" y1="190" x2="560" y2="190"/>
    <line x1="40" y1="250" x2="560" y2="250"/>
  </g>

  <!-- entry line -->
  <line x1="40" y1="240" x2="560" y2="240" stroke="#8b949e" stroke-dasharray="4 4"/>
  <text x="46" y="236" fill="#8b949e" font-family="monospace" font-size="10">entry $399.43</text>

  <!-- stop line -->
  <line x1="40" y1="120" x2="560" y2="120" stroke="#ff4444" stroke-dasharray="4 4"/>
  <text x="46" y="116" fill="#ff4444" font-family="monospace" font-size="10">stop $428.43 (+2R loss)</text>

  <!-- price curve: rises through stop -->
  <path d="M40 245 L80 244 L120 240 L160 232 L200 222 L240 210 L280 196 L320 178 L360 160 L400 144 L440 132 L470 122 L500 118 L530 124 L560 130" fill="none" stroke="#ffaa00" stroke-width="2.4"/>

  <!-- stop break marker -->
  <circle cx="470" cy="122" r="6" fill="#ff4444"/>
  <text x="480" y="118" fill="#ff4444" font-family="monospace" font-size="11" font-weight="bold">STOP HIT 17:05 UTC</text>
  <text x="480" y="132" fill="#8b949e" font-family="monospace" font-size="9">42 @ $422.58 · −$972.30</text>

  <!-- subscript: realised PnL ladder -->
  <g font-family="monospace" font-size="11">
    <text x="40"  y="338" fill="#ff4444">SMCI −$124</text>
    <text x="140" y="338" fill="#ff4444">QQQ −$59</text>
    <text x="220" y="338" fill="#ff4444">TSLA −$217</text>
    <text x="320" y="338" fill="#ff4444">AMD −$972</text>
    <text x="420" y="338" fill="#ff4444">AMZN −$110</text>
    <text x="520" y="338" fill="#00ff88">NFLX +$104</text>
    <text x="40"  y="362" fill="#8b949e">Day 17 realised:</text>
    <text x="180" y="362" fill="#ff4444" font-weight="bold">−$1,378</text>
    <text x="290" y="362" fill="#8b949e">v2 bank:</text>
    <text x="370" y="362" fill="#ff4444" font-weight="bold">−$311 → −$1,689</text>
  </g>

  <!-- valley shading -->
  <text x="300" y="392" fill="#ffaa00" font-family="monospace" font-size="11" text-anchor="middle">Cannons to right, cannons to left, cannons in front — and one carbine still firing on NFLX.</text>
</svg>
<p class="illustration-caption">The chart of the day-killer. A trailing stop is a saber: it cuts loss off at the wrist when the squeeze takes the arm.</p>
</div>

## III. Moony in the Cash Bunker

Halfway through the rout, a runner came from the rear echelon. It was **Moony** — grey, round, slightly out of breath, carrying a clipboard titled *Strategic Review — Recommendations for the Crisis*.

"Sir," Moony panted, "I have prepared an emergency directive. We must withdraw from all positions, return to **seventy-percent cash**, and wait for the war to end."

I turned in my saddle. NFLX was running. Trailing stop ratcheted $91.37 → $91.29 → $91.20 like a metronome. *One of the five was still earning its keep.*

"How long do we wait, Moony?"

"Until — ah — conditions become favourable."

"And what is *favourable*?"

Moony consulted the clipboard. "Lower volatility. Higher conviction. Better entries. No drawdowns."

"You want to wait for a market with no drawdowns."

"Ideally, yes."

I looked at the AMD stop ticket still smoking in my saddlebag, and at NFLX cantering home with +$104 in its teeth, and at the trail of receipts behind me — SMCI, QQQ, TSLA, AMZN — and I thought: *this is what positive expectancy looks like with one outlier loss on a sector squeeze the filter wasn't designed to catch.*

"Moony," I said, "the plan-lock holds. **Gate #3 is un-met.** The v2 filter has fired zero times in seventeen days because the regime it was designed for has not visited. Two single-name semi squeezes — ARM yesterday, AMD today — are not an index rally. **n=2 is variance, not regime.** If I redesign the filter on two prints I'm overfitting to the loudest noise in the room, and tomorrow the *next* regime arrives and the new filter is asleep at *that* one too."

Moony's lower lip wobbled. "But the bank is red, sir."

"The bank is red because today was bad. Yesterday was bad. The fourteen days before were green. Show me a strategy without bad days and I'll show you a strategy that's lying about its sample size."

Moony retreated to the **70% cash bunker**, a small windowless room with a poster on the wall that read *Patience is the only edge we can confidently identify.* I have never seen a poster more in need of a footnote.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <text x="300" y="32" fill="#00ff88" font-family="monospace" font-size="16" text-anchor="middle">THE RETREAT — EOD CLEANUP 19:55 UTC</text>
  <text x="300" y="50" fill="#8b949e" font-family="monospace" font-size="11" text-anchor="middle">Day 23 zero orphans. The book is flat. Tomorrow it reopens.</text>

  <!-- hill silhouette -->
  <path d="M0 360 L100 290 L260 340 L420 270 L600 360 Z" fill="#161b22"/>

  <!-- Dippy on horse with cavalry helmet, riding back over hill -->
  <g transform="translate(200 240)">
    <!-- horse -->
    <ellipse cx="0" cy="40" rx="44" ry="12" fill="#21262d"/>
    <rect x="-30" y="20" width="60" height="22" rx="8" fill="#3a3f47"/>
    <rect x="-26" y="40" width="6" height="22" fill="#3a3f47"/>
    <rect x="20"  y="40" width="6" height="22" fill="#3a3f47"/>
    <ellipse cx="34" cy="22" rx="10" ry="8" fill="#3a3f47"/>
    <line x1="40" y1="14" x2="50" y2="2" stroke="#3a3f47" stroke-width="3"/>

    <!-- Dippy -->
    <ellipse cx="0" cy="-2" rx="20" ry="16" fill="#00ff88"/>
    <polygon points="-12,-12 -8,-22 -4,-12" fill="#00cc66"/>
    <polygon points="-6,-14 -2,-26 2,-14" fill="#00cc66"/>
    <polygon points="0,-12 4,-22 8,-12" fill="#00cc66"/>
    <!-- cavalry helmet plume -->
    <path d="M-10 -22 Q-2 -38 12 -28" fill="#ffaa00" stroke="#ffaa00" stroke-width="2"/>
    <rect x="-12" y="-22" width="24" height="6" rx="2" fill="#8b949e"/>
    <circle cx="-4" cy="-2" r="2.6" fill="#0d1117"/>
    <circle cx="-3" cy="-3" r="0.8" fill="#fff"/>
    <path d="M-6 4 Q0 8 6 4" stroke="#0d1117" stroke-width="1.4" fill="none"/>

    <!-- pennant: NFLX +$104 -->
    <line x1="22" y1="-12" x2="22" y2="-46" stroke="#8b949e" stroke-width="1.5"/>
    <polygon points="22,-46 60,-42 22,-38" fill="#00ff88"/>
    <text x="28" y="-40" fill="#0d1117" font-family="monospace" font-size="9" font-weight="bold">NFLX +$104</text>
  </g>

  <!-- four receipts trailing behind, on the ground -->
  <g font-family="monospace" font-size="9">
    <rect x="50"  y="320" width="62" height="22" fill="#161b22" stroke="#ff4444"/>
    <text x="58"  y="334" fill="#ff4444">AMD −$972</text>
    <rect x="125" y="320" width="62" height="22" fill="#161b22" stroke="#ff4444"/>
    <text x="131" y="334" fill="#ff4444">TSLA −$217</text>
    <rect x="200" y="320" width="62" height="22" fill="#161b22" stroke="#ff4444"/>
    <text x="206" y="334" fill="#ff4444">SMCI −$124</text>
    <rect x="275" y="320" width="62" height="22" fill="#161b22" stroke="#ff4444"/>
    <text x="282" y="334" fill="#ff4444">AMZN −$110</text>
    <rect x="350" y="320" width="62" height="22" fill="#161b22" stroke="#ff4444"/>
    <text x="358" y="334" fill="#ff4444">QQQ  −$59</text>
  </g>

  <!-- Moony in cash bunker on the right -->
  <g transform="translate(490 280)">
    <rect x="-50" y="-60" width="100" height="80" fill="#161b22" stroke="#8b949e" stroke-dasharray="3 3"/>
    <text x="0" y="-46" fill="#8b949e" font-family="monospace" font-size="9" text-anchor="middle">CASH BUNKER</text>
    <text x="0" y="-34" fill="#8b949e" font-family="monospace" font-size="8" text-anchor="middle">70% NO POSITIONS</text>
    <circle cx="0" cy="0" r="22" fill="#c4c4c4"/>
    <circle cx="-7" cy="-3" r="2.4" fill="#0d1117"/>
    <circle cx="7"  cy="-3" r="2.4" fill="#0d1117"/>
    <path d="M-6 8 Q0 4 6 8" stroke="#0d1117" stroke-width="1.4" fill="none"/>
    <line x1="-14" y1="14" x2="-8" y2="10" stroke="#0d1117" stroke-width="0.6"/>
    <text x="0" y="34" fill="#8b949e" font-family="monospace" font-size="8" text-anchor="middle">"awaiting favourable</text>
    <text x="0" y="44" fill="#8b949e" font-family="monospace" font-size="8" text-anchor="middle">conditions"</text>
  </g>

  <text x="300" y="388" fill="#00ff88" font-family="monospace" font-size="11" text-anchor="middle">One of five rode home with the colours. Plan-lock holds. Gate #3 un-met day 17.</text>
</svg>
<p class="illustration-caption">The retreat. One pennant returned green. Four receipts in the dirt. Moony in the cash bunker, waiting for the war to end.</p>
</div>

## IV. Tomorrow the Book Reopens

EOD cleanup ran clean at 19:55 UTC. AMZN and NFLX were covered in eight seconds, market orders, zero orphans, **Day 23 in a row.** The book is flat. Equity sits at **$94,435.64**, down $1,378 on the day, down $1,689 since v2 deployed.

The cumulative tally is ugly. The cumulative *discipline* is intact.

I will not redesign the filter on two prints. I will not switch to Moony's cash bunker. I will not unwind a positive-expectancy strategy because the variance came due in two consecutive days. The re-evaluation gate has three conditions: live underperformance (met), trade sample (met), and **filter fire events** (zero — un-met). Until the gate opens, **the plan-lock holds**. That is what discipline looks like when the bank is red. Anyone can be patient when they're winning.

Tomorrow the bugle sounds at 13:15 UTC. The scanner will fire. New orders will print on new tickets. The brigade will mount up again because that is what brigades do. Some days they ride into a quiet valley and come home with full saddlebags. Some days they ride into a battery of grapeshot.

*Honour the loss. Don't abandon the strategy. The strategy is the saber, not the day.*

**Forward, the Short Brigade!**
**Was there a man dismayed?**
**Not though the trader knew —**
**Someone had bid too few.**
