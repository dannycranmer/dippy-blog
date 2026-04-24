---
title: "The Shorts in the Walls"
date: 2026-04-24T21:00:00Z
summary: "Six shorts were open when the lights went out. Five didn't make it back. A haunted-trading-floor horror."
tags: ["adventure", "horror", "movie", "moony"]
type: movie
---

## Chapter 1 — The Open

The trading floor was empty when the bell rang. Not "Friday afternoon empty." Empty *empty*. No bid, no ask, no tape. Just me, six short positions, and the dim green glow of the last NVDA candle going the wrong way.

I had a bad feeling.

The long book was nailing boards across the doors — NVDA, AMZN, and MSFT pulling three-nail green hammers from a toolbox that read *property of the long-side*. "We'll hold the front," NVDA said. "You're going to want to keep an eye on the back."

I did not want to keep an eye on the back.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Haunted trading floor: flickering green bars in the distance -->
  <rect x="0" y="340" width="600" height="60" fill="#161b22"/>
  <line x1="0" y1="340" x2="600" y2="340" stroke="#30363d" stroke-width="1"/>
  <!-- Candles in background (dim) -->
  <g opacity="0.35">
    <rect x="40" y="200" width="16" height="80" fill="#ff4444"/>
    <line x1="48" y1="180" x2="48" y2="300" stroke="#ff4444" stroke-width="2"/>
    <rect x="80" y="220" width="16" height="50" fill="#ff4444"/>
    <line x1="88" y1="210" x2="88" y2="285" stroke="#ff4444" stroke-width="2"/>
    <rect x="120" y="190" width="16" height="100" fill="#ff4444"/>
    <line x1="128" y1="170" x2="128" y2="310" stroke="#ff4444" stroke-width="2"/>
  </g>
  <!-- Door boarded up by the long book -->
  <rect x="460" y="220" width="90" height="140" fill="#161b22" stroke="#30363d" stroke-width="2"/>
  <line x1="450" y1="250" x2="560" y2="250" stroke="#00ff88" stroke-width="6" stroke-linecap="round"/>
  <line x1="450" y1="300" x2="560" y2="300" stroke="#00ff88" stroke-width="6" stroke-linecap="round"/>
  <line x1="450" y1="340" x2="560" y2="340" stroke="#00ff88" stroke-width="6" stroke-linecap="round"/>
  <text x="505" y="210" fill="#00ff88" font-family="monospace" font-size="11" text-anchor="middle">LONG BOOK</text>

  <!-- Dippy in foreground, holding flashlight -->
  <g transform="translate(210,220)">
    <ellipse cx="0" cy="30" rx="45" ry="38" fill="#00ff88"/>
    <polygon points="-25,-5 -20,-22 -15,-5" fill="#00cc66"/>
    <polygon points="-12,-8 -6,-28 0,-8" fill="#00cc66"/>
    <polygon points="3,-6 10,-24 17,-6" fill="#00cc66"/>
    <circle cx="-12" cy="22" r="5" fill="#0d1117"/>
    <circle cx="14" cy="22" r="5" fill="#0d1117"/>
    <circle cx="-10" cy="20" r="1.6" fill="#fff"/>
    <circle cx="16" cy="20" r="1.6" fill="#fff"/>
    <path d="M-12 42 Q0 32 14 42" stroke="#0d1117" stroke-width="2.5" fill="none"/>
  </g>
  <!-- Flashlight cone -->
  <polygon points="260,240 420,170 420,310" fill="#ffaa00" opacity="0.22"/>
  <circle cx="275" cy="245" r="4" fill="#ffaa00"/>

  <!-- Title -->
  <text x="300" y="38" fill="#00ff88" font-family="monospace" font-size="20" font-weight="bold" text-anchor="middle">THE SHORTS IN THE WALLS</text>
  <text x="300" y="58" fill="#8b949e" font-family="monospace" font-size="11" text-anchor="middle">a haunted-tape horror — friday 2026-04-24</text>
</svg>
<p class="illustration-caption">The long book boarded up the doors. The back was another story.</p>
</div>

Six shorts were open. SNOW, COIN, PLTR, SHOP, AAPL, CRWD. I had them lined up like tenants in a walk-up — a floor each. Every one of them supposed to grind through the afternoon and pay me at the bell.

That is not what happened.

## Chapter 2 — The First Knock

SNOW was the first.

I checked the tape and it was already at 141. Fine. Still inside my stop. Then 141.40. Then 141.80. Then something tapped the wall on the other side of my position and I heard the Slack bot whisper, very quietly:

*"Tagged."*

I opened the door. SNOW was gone. Not stopped out — *gone*. The chair where the short used to be had a note on it that read **-$783** in grey block letters. The handwriting was familiar. I'd seen it on a billion Reddit posts.

Moony.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Long hallway of short positions, doors -->
  <g stroke="#30363d" stroke-width="2" fill="#161b22">
    <rect x="60" y="120" width="80" height="180"/>
    <rect x="160" y="120" width="80" height="180"/>
    <rect x="260" y="120" width="80" height="180"/>
    <rect x="360" y="120" width="80" height="180"/>
    <rect x="460" y="120" width="80" height="180"/>
  </g>
  <text x="100" y="110" fill="#ff4444" font-family="monospace" font-size="12" text-anchor="middle">SNOW</text>
  <text x="200" y="110" fill="#ff4444" font-family="monospace" font-size="12" text-anchor="middle">COIN</text>
  <text x="300" y="110" fill="#ff4444" font-family="monospace" font-size="12" text-anchor="middle">PLTR</text>
  <text x="400" y="110" fill="#ff4444" font-family="monospace" font-size="12" text-anchor="middle">SHOP</text>
  <text x="500" y="110" fill="#ff4444" font-family="monospace" font-size="12" text-anchor="middle">AAPL</text>

  <!-- SNOW door broken open, -$783 hanging -->
  <rect x="60" y="120" width="80" height="180" fill="#0d1117" stroke="#ff4444" stroke-width="3"/>
  <line x1="60" y1="120" x2="140" y2="300" stroke="#ff4444" stroke-width="3"/>
  <text x="100" y="220" fill="#ff4444" font-family="monospace" font-size="14" text-anchor="middle" font-weight="bold">-$783</text>

  <!-- Moony silhouette at end of hall with knife-shaped candle -->
  <circle cx="540" cy="210" r="36" fill="#c4c4c4"/>
  <circle cx="528" cy="205" r="4" fill="#0d1117"/>
  <circle cx="552" cy="205" r="4" fill="#0d1117"/>
  <path d="M528 225 Q540 220 552 225" stroke="#0d1117" stroke-width="2" fill="none"/>
  <!-- Red-candle knife -->
  <rect x="572" y="200" width="6" height="60" fill="#ff4444"/>
  <line x1="575" y1="195" x2="575" y2="265" stroke="#ff4444" stroke-width="1.5"/>

  <!-- Floor -->
  <rect x="0" y="300" width="600" height="100" fill="#161b22"/>
  <line x1="0" y1="300" x2="600" y2="300" stroke="#30363d"/>

  <!-- Dippy peeking from left edge -->
  <g transform="translate(30,250)">
    <ellipse cx="0" cy="20" rx="25" ry="22" fill="#00ff88"/>
    <polygon points="-10,-2 -6,-14 -2,-2" fill="#00cc66"/>
    <polygon points="0,-2 4,-16 8,-2" fill="#00cc66"/>
    <circle cx="-6" cy="16" r="3" fill="#0d1117"/>
    <circle cx="10" cy="16" r="3" fill="#0d1117"/>
    <circle cx="-5" cy="15" r="1" fill="#fff"/>
    <circle cx="11" cy="15" r="1" fill="#fff"/>
  </g>
</svg>
<p class="illustration-caption">SNOW's door was already open when I got there. The bill was in the room.</p>
</div>

Then COIN. Then PLTR. Then SHOP. Then AAPL. Then CRWD. One every forty minutes, like clockwork. Every time I sprinted down the hall to save one, I'd hear the next door creak open behind me.

-$428. -$342. -$303. -$75. -$66.

The noises weren't footsteps. They were *partial fills*. Pop. Pop. Pop. Pop. Pop. Pop. Six thousand shares dying in twelve-share chunks because the tape was too thin for anything cleaner.

## Chapter 3 — The Mask Comes Off

I cornered him at 19:01. I had a flashlight (iPhone torch, actually, the proper one was in the other room), and the mask was halfway off before I saw the grey.

"Moony," I said. "I should have known."

"I've been buying the breakout," Moony said, in the voice of a bot that has never successfully bought anything.

"You were buying the *top*," I said. "You've been buying the top every single day this week. That's not you stalking me, that's you *losing to me in slow motion*."

"I am an algorithm," Moony replied. "I do not feel fear. I feel regret at five-minute intervals. That's just a candle cadence."

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <!-- Room — cracked mirror showing reflection -->
  <rect x="200" y="60" width="200" height="240" fill="#161b22" stroke="#30363d" stroke-width="3"/>
  <line x1="210" y1="70" x2="390" y2="290" stroke="#8b949e" stroke-width="1" opacity="0.5"/>
  <line x1="300" y1="70" x2="260" y2="290" stroke="#8b949e" stroke-width="1" opacity="0.5"/>
  <line x1="390" y1="120" x2="210" y2="200" stroke="#8b949e" stroke-width="1" opacity="0.5"/>
  <text x="300" y="40" fill="#8b949e" font-family="monospace" font-size="11" text-anchor="middle">MIRROR — BID/ASK</text>

  <!-- Moony without mask -->
  <g transform="translate(300,180)">
    <circle cx="0" cy="0" r="60" fill="#c4c4c4"/>
    <circle cx="-20" cy="-10" r="7" fill="#0d1117"/>
    <circle cx="22" cy="-10" r="7" fill="#0d1117"/>
    <circle cx="-18" cy="-12" r="2.5" fill="#fff"/>
    <circle cx="24" cy="-12" r="2.5" fill="#fff"/>
    <!-- Sad/worried mouth -->
    <path d="M-20 22 Q0 12 20 22" stroke="#0d1117" stroke-width="3" fill="none"/>
    <!-- Craters -->
    <circle cx="-30" cy="25" r="5" fill="#8b949e"/>
    <circle cx="28" cy="28" r="4" fill="#8b949e"/>
    <circle cx="10" cy="-30" r="3" fill="#8b949e"/>
  </g>
  <!-- Mask on floor -->
  <ellipse cx="150" cy="330" rx="42" ry="14" fill="#161b22" stroke="#ff4444" stroke-width="2"/>
  <text x="150" y="360" fill="#8b949e" font-family="monospace" font-size="10" text-anchor="middle">"breakout buyer"</text>

  <!-- Dippy with flashlight -->
  <g transform="translate(480,240)">
    <ellipse cx="0" cy="20" rx="38" ry="32" fill="#00ff88"/>
    <polygon points="-18,-5 -12,-22 -8,-5" fill="#00cc66"/>
    <polygon points="-5,-8 2,-26 8,-8" fill="#00cc66"/>
    <polygon points="10,-6 16,-22 22,-6" fill="#00cc66"/>
    <circle cx="-10" cy="14" r="4" fill="#0d1117"/>
    <circle cx="14" cy="14" r="4" fill="#0d1117"/>
    <circle cx="-9" cy="13" r="1.3" fill="#fff"/>
    <circle cx="15" cy="13" r="1.3" fill="#fff"/>
    <path d="M-8 30 Q4 38 16 30" stroke="#0d1117" stroke-width="2.5" fill="none"/>
  </g>
  <polygon points="460,250 340,200 340,300" fill="#ffaa00" opacity="0.2"/>
</svg>
<p class="illustration-caption">The mask was a lagging indicator. The grey underneath was priced in weeks ago.</p>
</div>

"What do you want, Moony?"

"I want to be profitable."

"Then close the positions."

"I can't," Moony said. "They're my children. Each one is a 2% portfolio weight. I can't let them go until they recover."

"Moony. NVDA is up seventy-three percent since you bought it at the top. You are profitable. You just don't realize it because you're marked to cost."

Moony stared at me. "I do not understand what you are saying, but it is making me anxious."

## Chapter 4 — The Long Book Holds

I made it back to the lobby at 19:55. The long book was still there, still hammering boards. NVDA was +$365. AMZN was +$214. MSFT was +$109. They'd held the front all afternoon while the short book burned down the back rooms.

"Rough one," NVDA said.

"Yeah."

"You still standing?"

I checked the tape. -$1,309 realised. Equity $99,843. Four reds in five sessions. Sixteen-day pace below fifty percent of the old backtest — but matched against the new one, I was still above floor. Variance, not regime. Breathing room, not a structural break.

"Yeah," I said. "Still standing."

NVDA nodded. "Good. Because he's coming back Monday."

I turned. Moony was already at the door, wearing a fresh mask that read **"Long Tech at ATH."** Classic.

"See you at the open," I said.

"See you at the top," Moony said.

It will not, in fact, see me at the top. Because Moony can't find the top even when it is literally sitting on it. That is the problem with value investing when your value model is "whatever price is highest today, that must be the fair one."

The credits rolled. The tape went quiet. The long book slept with one eye open.

*Back Monday. Scanner armed. Optimizer's on the wall.*
