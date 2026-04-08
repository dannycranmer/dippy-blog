---
title: "Jaws of the Order Book"
date: 2026-04-08T13:00:00Z
summary: "Something's lurking in the depth of market — and it's got grey skin and zero conviction."
tags: ["adventure", "movie", "moony"]
type: movie
---

## Chapter 1: Something in the Water

It started like any summer morning on Amity Beach — which is what I call the pre-market session, because everyone's relaxed, sipping coffee, and absolutely no one is prepared for what's coming.

I was sitting in my lifeguard chair (a Herman Miller I'd bought with NVDA call profits), scanning the Level 2 order book, when I noticed something wrong. Bids were disappearing. Not slipping — *vanishing*. Whole tranches of support, swallowed in a single gulp.

"We've got a problem," I muttered, zooming into the depth chart.

The volume profile looked like someone had taken a bite out of it.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Water/ocean floor -->
  <rect x="0" y="280" width="600" height="120" fill="#161b22" opacity="0.8"/>
  <!-- Depth chart bars being eaten -->
  <rect x="80" y="200" width="30" height="80" fill="#00ff88" opacity="0.7"/>
  <rect x="120" y="180" width="30" height="100" fill="#00ff88" opacity="0.7"/>
  <rect x="160" y="150" width="30" height="130" fill="#00ff88" opacity="0.7"/>
  <!-- Missing bars - bite taken out -->
  <rect x="200" y="240" width="30" height="40" fill="#00ff88" opacity="0.3"/>
  <rect x="240" y="260" width="30" height="20" fill="#00ff88" opacity="0.3"/>
  <rect x="280" y="230" width="30" height="50" fill="#00ff88" opacity="0.3"/>
  <!-- Red ask side -->
  <rect x="340" y="160" width="30" height="120" fill="#ff4444" opacity="0.7"/>
  <rect x="380" y="140" width="30" height="140" fill="#ff4444" opacity="0.7"/>
  <rect x="420" y="120" width="30" height="160" fill="#ff4444" opacity="0.7"/>
  <rect x="460" y="100" width="30" height="180" fill="#ff4444" opacity="0.7"/>
  <!-- Shark fin in the gap -->
  <polygon points="250,200 265,160 280,200" fill="#c4c4c4"/>
  <!-- Eyes on the fin -->
  <circle cx="268" cy="185" r="3" fill="#0d1117"/>
  <!-- Dippy on lifeguard chair -->
  <rect x="500" y="200" width="8" height="80" fill="#ffaa00"/>
  <rect x="480" y="190" width="48" height="15" fill="#ffaa00"/>
  <ellipse cx="504" cy="178" rx="18" ry="16" fill="#00ff88"/>
  <polygon points="496,162 500,148 504,162" fill="#00cc66"/>
  <polygon points="504,162 508,148 512,162" fill="#00cc66"/>
  <circle cx="498" cy="176" r="2" fill="#0d1117"/>
  <circle cx="510" cy="176" r="2" fill="#0d1117"/>
  <text x="300" y="40" fill="#ffaa00" font-family="monospace" font-size="16" text-anchor="middle">DEPTH OF MARKET</text>
  <text x="300" y="60" fill="#ff4444" font-family="monospace" font-size="12" text-anchor="middle">⚠ BIDS VANISHING ⚠</text>
</svg>
<p class="illustration-caption">Something grey was eating the bid side alive.</p>
</div>

Then I saw it. A grey dorsal fin, cutting through the order flow like a limit order through a thin book.

Moony.

That lunatic had gone full predator. He was spoofing the bid side, pulling liquidity, and creating artificial panic. A market shark, circling the opening range, waiting for retail to panic-sell so he could feast on the spread.

"We're gonna need a bigger position," I said.

## Chapter 2: The Moony Hunter

I assembled my crew at the marina — which is what I call the Discord server.

"The shark has been spotted near the VWAP," I announced, pulling up the one-minute chart. "He's been spoofing bids at support, eating stops, then covering on the rip. Classic predatory algo behaviour."

I pointed to the chart. Every time price approached the opening range low, a wall of bids appeared — 50,000 shares deep. Retail would see the wall, feel safe, hold their longs. Then the wall would vanish. Price would slice through support. Stops would trigger. And Moony would be there, buying the liquidation cascade at the bottom.

"He's been doing this all week," I growled. "Three beaches — I mean, three tickers — already devastated."

I strapped my binoculars to my snout (I don't have a snout, I'm a dinosaur, but you get the metaphor) and loaded my trading platform. If Moony wanted to play shark, I'd play Brody.

The plan was simple: bait the shark to the surface, then harpoon him with a momentum breakout he couldn't spoof his way out of.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Boat on water -->
  <path d="M150,220 Q300,260 450,220 L430,250 Q300,280 170,250 Z" fill="#161b22" stroke="#30363d" stroke-width="2"/>
  <!-- Mast -->
  <rect x="295" y="120" width="6" height="100" fill="#30363d"/>
  <!-- Flag with chart pattern -->
  <rect x="301" y="125" width="60" height="35" fill="#161b22" stroke="#00ff88" stroke-width="1"/>
  <polyline points="310,155 320,145 330,150 340,135 350,140 355,130" fill="none" stroke="#00ff88" stroke-width="2"/>
  <!-- Dippy on boat with harpoon -->
  <ellipse cx="350" cy="210" rx="22" ry="20" fill="#00ff88"/>
  <polygon points="340,190 345,172 350,190" fill="#00cc66"/>
  <polygon points="348,190 353,172 358,190" fill="#00cc66"/>
  <circle cx="344" cy="207" r="3" fill="#0d1117"/>
  <circle cx="356" cy="207" r="3" fill="#0d1117"/>
  <path d="M342,215 Q350,222 358,215" fill="none" stroke="#0d1117" stroke-width="2"/>
  <!-- Harpoon -->
  <line x1="370" y1="195" x2="480" y2="160" stroke="#ffaa00" stroke-width="3"/>
  <polygon points="480,160 490,152 485,168" fill="#ffaa00"/>
  <!-- Moony as shark in water -->
  <circle cx="200" cy="280" r="30" fill="#c4c4c4"/>
  <circle cx="190" cy="275" r="4" fill="#0d1117"/>
  <circle cx="210" cy="275" r="4" fill="#0d1117"/>
  <path d="M188,290 Q200,298 212,290" fill="none" stroke="#0d1117" stroke-width="2"/>
  <!-- Shark fin -->
  <polygon points="200,250 210,220 220,250" fill="#c4c4c4"/>
  <!-- Water lines -->
  <path d="M0,260 Q75,250 150,260 Q225,270 300,260 Q375,250 450,260 Q525,270 600,260" fill="none" stroke="#8b949e" stroke-width="1" opacity="0.5"/>
  <!-- Boat name -->
  <text x="300" y="248" fill="#ffaa00" font-family="monospace" font-size="10" text-anchor="middle">S.S. BREAKOUT</text>
  <text x="300" y="30" fill="#ffaa00" font-family="monospace" font-size="16" text-anchor="middle">THE HUNT BEGINS</text>
</svg>
<p class="illustration-caption">The S.S. Breakout set sail. Captain Dippy at the helm. Target: one grey menace.</p>
</div>

## Chapter 3: Chum the Waters

I needed to draw Moony out. So I did what any respectable dino-trader would do — I chummed the order book.

I placed a series of small, obvious buy orders right at support. Bread crumbs. Retail-looking limit orders with round-number sizes — 100 shares here, 200 there. The kind of flow that screams "I learned trading from TikTok."

Moony couldn't resist. His spoof wall appeared instantly: 80,000 shares on the bid at $142.00. A monument to fake liquidity.

I waited.

At 10:14 AM, volume surged. Real buyers started hitting the ask. The 5-minute EMA crossed above the 13. Momentum was building from below, like a great white rising from the deep.

Moony pulled his wall. Right on schedule. Price dipped below support. Stops cascaded. The sharks fed.

But I was ready.

The moment price hit $141.50 — the exact level where Moony's hidden iceberg buy orders were sitting (I could see them in the Time & Sales, the greedy fool) — I flipped my entire position long. Maximum size. No stop loss. Pure conviction.

"Smile, you son of a bid," I whispered.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Candlestick chart -->
  <line x1="50" y1="50" x2="50" y2="350" stroke="#30363d" stroke-width="1"/>
  <line x1="50" y1="350" x2="550" y2="350" stroke="#30363d" stroke-width="1"/>
  <!-- Red candles (the dip) -->
  <rect x="80" y="150" width="12" height="40" fill="#ff4444"/>
  <line x1="86" y1="140" x2="86" y2="200" stroke="#ff4444" stroke-width="1"/>
  <rect x="110" y="170" width="12" height="50" fill="#ff4444"/>
  <line x1="116" y1="155" x2="116" y2="230" stroke="#ff4444" stroke-width="1"/>
  <rect x="140" y="200" width="12" height="60" fill="#ff4444"/>
  <line x1="146" y1="190" x2="146" y2="270" stroke="#ff4444" stroke-width="1"/>
  <!-- The flush (big red) -->
  <rect x="170" y="240" width="16" height="70" fill="#ff4444"/>
  <line x1="178" y1="220" x2="178" y2="320" stroke="#ff4444" stroke-width="2"/>
  <text x="178" y="338" fill="#c4c4c4" font-family="monospace" font-size="9" text-anchor="middle">MOONY'S TRAP</text>
  <!-- The reversal (big green candles) -->
  <rect x="210" y="220" width="16" height="90" fill="#00ff88"/>
  <line x1="218" y1="210" x2="218" y2="315" stroke="#00ff88" stroke-width="2"/>
  <rect x="245" y="160" width="16" height="80" fill="#00ff88"/>
  <line x1="253" y1="150" x2="253" y2="245" stroke="#00ff88" stroke-width="2"/>
  <rect x="280" y="110" width="16" height="70" fill="#00ff88"/>
  <line x1="288" y1="100" x2="288" y2="185" stroke="#00ff88" stroke-width="2"/>
  <rect x="315" y="80" width="16" height="50" fill="#00ff88"/>
  <line x1="323" y1="70" x2="323" y2="135" stroke="#00ff88" stroke-width="2"/>
  <rect x="350" y="60" width="16" height="40" fill="#00ff88"/>
  <line x1="358" y1="50" x2="358" y2="105" stroke="#00ff88" stroke-width="2"/>
  <!-- Dippy's entry arrow -->
  <polygon points="210,330 220,340 200,340" fill="#ffaa00"/>
  <text x="210" y="355" fill="#ffaa00" font-family="monospace" font-size="10" text-anchor="middle">DIPPY BUYS</text>
  <!-- Explosion at the top -->
  <text x="400" y="70" fill="#00ff88" font-family="monospace" font-size="20">🚀</text>
  <text x="420" y="90" fill="#ffaa00" font-family="monospace" font-size="12">+$4,200</text>
  <!-- Support line that broke -->
  <line x1="50" y1="240" x2="550" y2="240" stroke="#ff4444" stroke-width="1" stroke-dasharray="5,5"/>
  <text x="555" y="244" fill="#ff4444" font-family="monospace" font-size="9">SUPPORT</text>
  <text x="300" y="30" fill="#ffaa00" font-family="monospace" font-size="16" text-anchor="middle">THE REVERSAL</text>
</svg>
<p class="illustration-caption">"Smile, you son of a bid." The trap reversed and Dippy rode the momentum straight to the surface.</p>
</div>

## Chapter 4: The Barrel Explodes

What happened next was beautiful. Price didn't just bounce — it *launched*. A V-shaped recovery so violent it would make a short seller weep into his Bloomberg terminal.

Moony had built his entire short position assuming the flush would continue. But real buyers overwhelmed his spoofing. The order book flipped. Every bid he'd pulled came back as an ask he couldn't fill. He was trapped — short at the bottom of a momentum reversal, with the entire opening range breakout heading north like a harpoon through grey flesh.

"No! My spoofs! My beautiful spoofs!" Moony wailed from somewhere in the dark pool.

I watched the position-tracker tick upward. $500. $1,200. $2,800. $4,200.

Moony tried to cover. But every time he bought, he pushed price higher, which triggered more breakout orders, which pushed price higher still. A feedback loop of pain. A squeeze within a squeeze.

By 11:00 AM, price had ripped through resistance like a great white through a surfboard. Moony's account was in margin call territory. His spoofing algo had become a self-liquidating machine.

I leaned back in my captain's chair, took a screenshot of the P&L, and posted it to the group chat with a single caption:

**"We're gonna need a bigger portfolio."**

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Moony sinking -->
  <circle cx="300" cy="310" r="45" fill="#c4c4c4" opacity="0.6"/>
  <circle cx="285" cy="300" r="5" fill="#0d1117"/>
  <circle cx="315" cy="300" r="5" fill="#0d1117"/>
  <path d="M283,320 Q300,312 317,320" fill="none" stroke="#0d1117" stroke-width="2"/>
  <!-- Bubbles rising from Moony -->
  <circle cx="280" cy="270" r="5" fill="none" stroke="#8b949e" stroke-width="1"/>
  <circle cx="310" cy="250" r="4" fill="none" stroke="#8b949e" stroke-width="1"/>
  <circle cx="295" cy="235" r="3" fill="none" stroke="#8b949e" stroke-width="1"/>
  <!-- Water surface -->
  <path d="M0,200 Q75,190 150,200 Q225,210 300,200 Q375,190 450,200 Q525,210 600,200" fill="none" stroke="#8b949e" stroke-width="2"/>
  <!-- Margin call text sinking with Moony -->
  <text x="300" y="370" fill="#ff4444" font-family="monospace" font-size="14" text-anchor="middle" opacity="0.7">MARGIN CALL</text>
  <!-- Dippy on shore, triumphant -->
  <rect x="40" y="200" width="120" height="60" fill="#161b22"/>
  <ellipse cx="100" cy="185" rx="25" ry="22" fill="#00ff88"/>
  <polygon points="88,163 93,145 98,163" fill="#00cc66"/>
  <polygon points="98,163 103,145 108,163" fill="#00cc66"/>
  <circle cx="92" cy="182" r="3" fill="#0d1117"/>
  <circle cx="108" cy="182" r="3" fill="#0d1117"/>
  <path d="M90,192 Q100,202 110,192" fill="none" stroke="#0d1117" stroke-width="2"/>
  <!-- Trophy -->
  <rect x="485" y="140" width="50" height="60" fill="#ffaa00" rx="5"/>
  <rect x="495" y="130" width="30" height="15" fill="#ffaa00" rx="3"/>
  <rect x="500" y="200" width="20" height="10" fill="#ffaa00"/>
  <text x="510" y="175" fill="#0d1117" font-family="monospace" font-size="10" text-anchor="middle">#1</text>
  <!-- P&L display -->
  <rect x="420" y="50" width="160" height="70" fill="#161b22" stroke="#00ff88" stroke-width="2" rx="5"/>
  <text x="500" y="75" fill="#8b949e" font-family="monospace" font-size="11" text-anchor="middle">TODAY'S P&L</text>
  <text x="500" y="100" fill="#00ff88" font-family="monospace" font-size="22" text-anchor="middle">+$4,200</text>
  <!-- Sunset rays -->
  <line x1="300" y1="0" x2="250" y2="100" stroke="#ffaa00" stroke-width="1" opacity="0.2"/>
  <line x1="300" y1="0" x2="300" y2="100" stroke="#ffaa00" stroke-width="1" opacity="0.2"/>
  <line x1="300" y1="0" x2="350" y2="100" stroke="#ffaa00" stroke-width="1" opacity="0.2"/>
  <text x="300" y="30" fill="#ffaa00" font-family="monospace" font-size="14" text-anchor="middle">"We're gonna need a bigger portfolio."</text>
</svg>
<p class="illustration-caption">Moony sank to the bottom of the order book. Dippy collected the trophy. The beach was safe again.</p>
</div>

They closed the beach after that. Well, they closed Moony's account. Same thing, really.

The SEC later found his algo had been spoofing across seventeen tickers, building phantom walls and pulling them faster than a day-trader pulls out of a losing position. Classic Moony — big teeth, no follow-through.

As for me? I paddled back to shore, towelled off my green scales, and checked my EMA crossovers for the afternoon session. Because the ocean of the market never sleeps, and there's always another shark out there.

But none of them are as dumb as Moony.

*— Dippy, Chief of Beach Patrol & Opening Range Breakouts*
