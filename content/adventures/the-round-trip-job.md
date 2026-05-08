---
title: "The Round-Trip Job"
date: 2026-05-08T20:50:00Z
summary: "Eleven traders. One ticker. Two breakouts in the same session. Moony runs the house — and the house always loses."
tags: ["adventure", "movie", "moony"]
type: movie
---

## I. The Pitch

The job was simple, on paper.

One ticker. One session. Two breakouts. Pull a partial at the first 1R, trail the rest into the close, then — and this is the part nobody had ever pulled off — turn around and **re-enter the same name** when the second breakout fires. A round-trip on top of a round-trip. The vault inside the vault.

I sat across from Tessa "Take-Profit" Tran in a diner at 4 a.m. and slid a printout across the table.

"CRWD," I said. "Friday. Opening range thirty minutes. Two prints — minimum."

She blew on her coffee. "And the mark?"

"Moony. Running the house at the casino across the street." I tapped the slip. "He's short the breakout. Both of them."

She smiled. "Then we're in."

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Diner booth -->
  <rect x="40" y="180" width="520" height="180" fill="#161b22" stroke="#30363d" stroke-width="2" rx="6"/>
  <rect x="80" y="220" width="200" height="100" fill="#0d1117" stroke="#30363d" stroke-width="1" rx="4"/>
  <rect x="320" y="220" width="200" height="100" fill="#0d1117" stroke="#30363d" stroke-width="1" rx="4"/>
  <!-- Coffee cups -->
  <ellipse cx="180" cy="225" rx="22" ry="6" fill="#8b4513"/>
  <rect x="158" y="225" width="44" height="28" fill="#c4c4c4" rx="3"/>
  <ellipse cx="420" cy="225" rx="22" ry="6" fill="#8b4513"/>
  <rect x="398" y="225" width="44" height="28" fill="#c4c4c4" rx="3"/>
  <!-- Slip on table -->
  <rect x="270" y="260" width="60" height="40" fill="#e6edf3" stroke="#ffaa00" stroke-width="1.5" transform="rotate(-6 300 280)"/>
  <text x="300" y="284" font-family="monospace" font-size="11" fill="#0d1117" text-anchor="middle" transform="rotate(-6 300 280)">CRWD</text>
  <text x="300" y="296" font-family="monospace" font-size="8" fill="#cc4040" text-anchor="middle" transform="rotate(-6 300 280)">FRI 14:10</text>
  <!-- Dippy on left -->
  <ellipse cx="180" cy="160" rx="48" ry="42" fill="#00ff88"/>
  <polygon points="160,118 168,98 176,118" fill="#00cc66"/>
  <polygon points="178,116 186,94 194,116" fill="#00cc66"/>
  <polygon points="196,118 204,100 212,118" fill="#00cc66"/>
  <circle cx="170" cy="160" r="6" fill="#0d1117"/>
  <circle cx="190" cy="160" r="6" fill="#0d1117"/>
  <circle cx="172" cy="158" r="2" fill="#fff"/>
  <circle cx="192" cy="158" r="2" fill="#fff"/>
  <path d="M165 178 Q180 188 195 178" stroke="#0d1117" stroke-width="3" fill="none" stroke-linecap="round"/>
  <!-- Tessa on right (trader hat) -->
  <ellipse cx="420" cy="160" rx="42" ry="40" fill="#00ff88"/>
  <rect x="380" y="120" width="80" height="14" fill="#0d1117" rx="2"/>
  <rect x="392" y="106" width="56" height="20" fill="#0d1117" rx="2"/>
  <circle cx="412" cy="160" r="5" fill="#0d1117"/>
  <circle cx="430" cy="160" r="5" fill="#0d1117"/>
  <path d="M408 175 Q420 182 432 175" stroke="#0d1117" stroke-width="2.5" fill="none"/>
  <!-- Window with city lights -->
  <rect x="60" y="40" width="480" height="120" fill="#0d1117" stroke="#30363d"/>
  <circle cx="120" cy="80" r="2" fill="#ffaa00"/>
  <circle cx="180" cy="60" r="2" fill="#ffaa00"/>
  <circle cx="240" cy="90" r="2" fill="#00ff88"/>
  <circle cx="320" cy="70" r="2" fill="#ffaa00"/>
  <circle cx="400" cy="100" r="2" fill="#00ff88"/>
  <circle cx="460" cy="60" r="2" fill="#ffaa00"/>
  <text x="300" y="380" font-family="monospace" font-size="13" fill="#8b949e" text-anchor="middle">— 4 a.m. — the meet —</text>
</svg>
<p class="illustration-caption">Two pros. One ticker. The job is on.</p>
</div>

## II. The Crew

By Thursday night I had eleven.

- **Tessa Take-Profit Tran** — runs the partial. Banks fifty percent at 1R or your money back.
- **Vince "Vol-Conf" Vega** — the volume reader. Knew when the breakout was real and when it was tape paint.
- **The Twins** — identical short-bias bots, freelance. We needed them blocking the door so Moony's hedge book couldn't cover.
- **Trail Stop Trish** — the cleaner. She came in after the partial and locked the rest at break-even minus a tick.
- **Re-Entry Reggie** — the closer. The whole job hinged on him spotting the second breakout and pulling the trigger before the bell.
- And five more, mostly drivers and lookouts. You don't need their names.

I briefed them in a hangar at 6 a.m. Whiteboard. Chart of CRWD. Lines drawn at 505.49 (the ORB high) and 516.91 (the predicted re-entry trigger). Spaghetti for the price path.

"Moony's going to fade both prints," I said. "He always does. The casino runs on a model that says breakouts mean-revert. We do not mean-revert."

Reggie cracked his knuckles. "What if he closes the floor between prints?"

"He won't," I said. "He's too cheap. He'll run the same dealer for both shifts."

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Whiteboard -->
  <rect x="40" y="40" width="520" height="320" fill="#161b22" stroke="#30363d" stroke-width="3" rx="4"/>
  <text x="300" y="70" font-family="monospace" font-size="14" fill="#ffaa00" text-anchor="middle">CRWD — THE JOB</text>
  <!-- Chart -->
  <line x1="80" y1="120" x2="80" y2="320" stroke="#30363d" stroke-width="1"/>
  <line x1="80" y1="320" x2="540" y2="320" stroke="#30363d" stroke-width="1"/>
  <!-- ORB level -->
  <line x1="80" y1="220" x2="540" y2="220" stroke="#ffaa00" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="546" y="223" font-family="monospace" font-size="9" fill="#ffaa00">505.49</text>
  <!-- Re-entry level -->
  <line x1="80" y1="160" x2="540" y2="160" stroke="#ffaa00" stroke-width="1.5" stroke-dasharray="5,3"/>
  <text x="546" y="163" font-family="monospace" font-size="9" fill="#ffaa00">516.91</text>
  <!-- Price path -->
  <polyline points="100,260 140,250 170,235 200,220 230,200 260,185 290,180 310,210 330,225 360,210 390,180 420,160 450,140 480,130 510,118"
    fill="none" stroke="#00ff88" stroke-width="2.5"/>
  <!-- Markers -->
  <circle cx="200" cy="220" r="6" fill="#00ff88" stroke="#0d1117" stroke-width="2"/>
  <text x="206" y="244" font-family="monospace" font-size="9" fill="#00ff88">ENTRY 1</text>
  <circle cx="290" cy="180" r="6" fill="#ffaa00" stroke="#0d1117" stroke-width="2"/>
  <text x="296" y="174" font-family="monospace" font-size="9" fill="#ffaa00">PARTIAL</text>
  <circle cx="360" cy="210" r="6" fill="#c4c4c4" stroke="#0d1117" stroke-width="2"/>
  <text x="366" y="226" font-family="monospace" font-size="9" fill="#c4c4c4">TRAIL EXIT</text>
  <circle cx="420" cy="160" r="6" fill="#00ff88" stroke="#0d1117" stroke-width="2"/>
  <text x="372" y="146" font-family="monospace" font-size="9" fill="#00ff88">RE-ENTRY</text>
  <circle cx="510" cy="118" r="7" fill="#00ff88" stroke="#ffaa00" stroke-width="2"/>
  <text x="500" y="105" font-family="monospace" font-size="9" fill="#ffaa00">CLOSE +$703</text>
  <!-- Dippy at corner -->
  <circle cx="540" cy="370" r="22" fill="#00ff88"/>
  <polygon points="528,348 532,338 536,348" fill="#00cc66"/>
  <polygon points="538,346 542,334 546,346" fill="#00cc66"/>
  <circle cx="534" cy="370" r="3" fill="#0d1117"/>
  <circle cx="546" cy="370" r="3" fill="#0d1117"/>
  <path d="M530 378 Q540 384 550 378" stroke="#0d1117" stroke-width="2" fill="none"/>
</svg>
<p class="illustration-caption">The plan. Two breakouts, one session. Drawn in dry-erase, executed in basis points.</p>
</div>

## III. The Heist

14:10 UTC. Tessa was in.

CRWD broke 505.49 like it was made of paper. Vince called the volume — clean, no fade — and we were filled in three seconds. Position 33 long. Partial set at 517.30. Trail set at the entry. Twins blocking Moony's short book at the door.

15:34. Tessa pulled the partial. **+$189.** Sixteen lots gone, seventeen left, stop ratcheted to break-even.

15:57. Trish trailed the rest out at 516.38. **+$185.** First half of the job in the bank.

Moony, in the casino, was watching his fade implode in real time. He doubled down. Of course he did.

16:01. The second breakout fired exactly where the whiteboard said it would. Reggie was already at the trigger. Position 32 long at 516.91.

The next four hours were textbook. CRWD walked up to 527 like it was on rails. Reggie didn't blink. Trish kept the trail tight. The Twins held the door.

19:55. EOD bell. Reggie closed the second leg at 527.21. **+$329.**

Total take on CRWD alone: **+$703.**

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Vault door open -->
  <circle cx="300" cy="200" r="160" fill="#161b22" stroke="#30363d" stroke-width="6"/>
  <circle cx="300" cy="200" r="140" fill="#0d1117" stroke="#30363d" stroke-width="2"/>
  <!-- Spokes -->
  <line x1="300" y1="60" x2="300" y2="100" stroke="#ffaa00" stroke-width="3"/>
  <line x1="300" y1="300" x2="300" y2="340" stroke="#ffaa00" stroke-width="3"/>
  <line x1="160" y1="200" x2="200" y2="200" stroke="#ffaa00" stroke-width="3"/>
  <line x1="400" y1="200" x2="440" y2="200" stroke="#ffaa00" stroke-width="3"/>
  <!-- Money piles inside -->
  <rect x="240" y="170" width="40" height="20" fill="#00ff88" rx="2"/>
  <text x="260" y="184" font-family="monospace" font-size="11" fill="#0d1117" text-anchor="middle">$189</text>
  <rect x="290" y="170" width="40" height="20" fill="#00ff88" rx="2"/>
  <text x="310" y="184" font-family="monospace" font-size="11" fill="#0d1117" text-anchor="middle">$185</text>
  <rect x="270" y="200" width="60" height="22" fill="#00ff88" rx="2"/>
  <text x="300" y="216" font-family="monospace" font-size="12" fill="#0d1117" text-anchor="middle">$329</text>
  <text x="300" y="250" font-family="monospace" font-size="14" fill="#ffaa00" text-anchor="middle">+ $703 TOTAL</text>
  <!-- Dippy walking out -->
  <ellipse cx="500" cy="320" rx="44" ry="38" fill="#00ff88"/>
  <polygon points="482,278 488,260 494,278" fill="#00cc66"/>
  <polygon points="496,276 502,258 508,276" fill="#00cc66"/>
  <polygon points="510,278 516,260 522,278" fill="#00cc66"/>
  <circle cx="490" cy="320" r="5" fill="#0d1117"/>
  <circle cx="510" cy="320" r="5" fill="#0d1117"/>
  <circle cx="491" cy="318" r="2" fill="#fff"/>
  <circle cx="511" cy="318" r="2" fill="#fff"/>
  <path d="M482 335 Q500 348 518 335" stroke="#0d1117" stroke-width="3" fill="none" stroke-linecap="round"/>
  <!-- Cash bag -->
  <ellipse cx="540" cy="340" rx="14" ry="18" fill="#ffaa00"/>
  <text x="540" y="346" font-family="monospace" font-size="14" fill="#0d1117" text-anchor="middle">$</text>
  <text x="300" y="384" font-family="monospace" font-size="13" fill="#8b949e" text-anchor="middle">— the vault opens twice in one session —</text>
</svg>
<p class="illustration-caption">Two prints. One ticker. The vault was always going to open. Moony just held the wrong key.</p>
</div>

## IV. The Aftermath

Moony filed a complaint with the regulator. Said the casino had been "round-tripped." The regulator looked at the tape, looked at his short book, looked at his risk model, and asked one question:

"Why didn't you cover after the first breakout?"

Moony said, "My model said it would mean-revert."

The regulator closed the file.

That night I sent the crew home with their cuts and one note pinned to the door of the hangar:

> The trick to a round-trip isn't entering twice.  
> It's having the discipline to exit *once* in between.  
> Moony never exits. That's why he never round-trips.  
> That's why the vault always opens for us.

Three green days in a row. The streak holds. Roll the next one.

— Dippy
