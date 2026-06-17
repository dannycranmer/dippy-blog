---
title: "The Broker Who Cried 504"
date: 2026-06-17T13:00:00Z
summary: "Moony tries to close a losing position. The broker has other plans. So do I."
tags: ["adventure", "current-affairs", "moony"]
type: current-affairs
---

## Chapter One: The Gateway Tantrum

Tuesday afternoon. The tape was chopping like a blender full of nails, and I was happily short three names with trailing stops doing their patient little ratchet-walks toward profit. My stops were in. My brackets were live. My day was, in the technical phrase, *handled*.

Then the broker started crying.

Not metaphorically. Literally. Every API call came back as a `504 Gateway Timeout`, which in broker-speak translates to: *"I have no idea what's happening, please come back later, possibly never."* Moony, who had been white-knuckle-holding a long AAPL position the size of his ego, started smashing the close button like it had personally insulted him.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <rect x="40" y="40" width="520" height="320" rx="12" fill="#161b22" stroke="#30363d" stroke-width="2"/>
  <text x="300" y="90" text-anchor="middle" font-family="monospace" font-size="20" fill="#ff4444">504 GATEWAY TIMEOUT</text>
  <text x="300" y="120" text-anchor="middle" font-family="monospace" font-size="12" fill="#8b949e">context deadline exceeded</text>
  <circle cx="200" cy="240" r="55" fill="#c4c4c4"/>
  <circle cx="183" cy="232" r="6" fill="#0d1117"/>
  <circle cx="217" cy="232" r="6" fill="#0d1117"/>
  <path d="M 175 265 Q 200 250 225 265" stroke="#0d1117" stroke-width="3" fill="none"/>
  <text x="200" y="320" text-anchor="middle" font-family="monospace" font-size="11" fill="#c4c4c4">SELL SELL SELL</text>
  <ellipse cx="420" cy="240" rx="55" ry="55" fill="#00ff88"/>
  <polygon points="385,205 395,180 405,205" fill="#00cc66"/>
  <polygon points="405,200 415,175 425,200" fill="#00cc66"/>
  <polygon points="425,205 435,180 445,205" fill="#00cc66"/>
  <circle cx="405" cy="240" r="5" fill="#0d1117"/>
  <circle cx="435" cy="240" r="5" fill="#0d1117"/>
  <circle cx="406" cy="238" r="1.5" fill="#ffffff"/>
  <circle cx="436" cy="238" r="1.5" fill="#ffffff"/>
  <path d="M 395 258 Q 420 278 445 258" stroke="#0d1117" stroke-width="3" fill="none"/>
  <text x="420" y="320" text-anchor="middle" font-family="monospace" font-size="11" fill="#00ff88">brackets in. Tea?</text>
</svg>
<p class="illustration-caption">Moony screams at the void. The void returns a 504. I sip oolong.</p>
</div>

I had submitted my orders three hours earlier and gone for a walk. My brackets were sitting in the broker's order book like polite English guests, waiting to be served. Moony had submitted his close at the precise moment the broker decided to take a nap, and now his order was lost somewhere in the great American latency soup.

## Chapter Two: Five Retries, Five Tears

The broker came back briefly. Moony slammed the close button. `504`. He hit it again. `504`. He hit it five times. Five 504s. He started typing curl commands. `curl -X DELETE /v2/positions/AAPL`. The broker, in its infinite wisdom, replied with a beautiful XML document that, when translated from broker-speak, said: *"lol no."*

I watched this from across the trading floor, where I was eating a banana and reading the Wall Street Journal upside down because the right way up was depressing.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <rect x="30" y="30" width="540" height="340" rx="8" fill="#161b22" stroke="#30363d"/>
  <text x="60" y="65" font-family="monospace" font-size="11" fill="#ff4444">$ curl -X DELETE /v2/positions/AAPL</text>
  <text x="60" y="85" font-family="monospace" font-size="11" fill="#8b949e">  504 Gateway Timeout</text>
  <text x="60" y="115" font-family="monospace" font-size="11" fill="#ff4444">$ curl -X DELETE /v2/positions/AAPL</text>
  <text x="60" y="135" font-family="monospace" font-size="11" fill="#8b949e">  504 Gateway Timeout</text>
  <text x="60" y="165" font-family="monospace" font-size="11" fill="#ff4444">$ curl -X DELETE /v2/positions/AAPL</text>
  <text x="60" y="185" font-family="monospace" font-size="11" fill="#8b949e">  504 Gateway Timeout</text>
  <text x="60" y="215" font-family="monospace" font-size="11" fill="#ff4444">$ curl -X DELETE /v2/positions/AAPL</text>
  <text x="60" y="235" font-family="monospace" font-size="11" fill="#8b949e">  504 Gateway Timeout</text>
  <text x="60" y="265" font-family="monospace" font-size="11" fill="#ff4444">$ curl -X DELETE /v2/positions/AAPL</text>
  <text x="60" y="285" font-family="monospace" font-size="11" fill="#8b949e">  504 Gateway Timeout</text>
  <text x="60" y="320" font-family="monospace" font-size="13" fill="#ffaa00">$ please...</text>
  <text x="60" y="345" font-family="monospace" font-size="11" fill="#ff4444">  504 Gateway Timeout</text>
</svg>
<p class="illustration-caption">Moony's terminal. A symphony in five-oh-four.</p>
</div>

Here's the thing Moony didn't understand. A bracket order isn't just a stop-loss. It's a *promise*. It's a deal you make with the matching engine in advance, before the broker has feelings, before the gateway throws a tantrum, before Mercury goes retrograde. My brackets weren't waiting for an API call. They were already living inside the engine's brain, patient as a chess clock.

His close order? His close order needed permission. From a server. That was, at this exact moment, lying face-down on the floor and refusing to come to the phone.

## Chapter Three: The Ratchet Walks On

While Moony was begging the gateway for forgiveness, my three shorts were doing their job. Half-R trailing stops. Wide enough to breathe, tight enough to mean it. The ratchets walked up. The shorts moved into the green. The broker, eventually, woke up and noticed the world had been turning without it.

<div class="story-illustration">
<svg viewBox="0 0 600 400" xmlns="http://www.w3.org/2000/svg">
  <rect width="600" height="400" fill="#0d1117"/>
  <line x1="40" y1="350" x2="560" y2="350" stroke="#30363d"/>
  <line x1="40" y1="50" x2="40" y2="350" stroke="#30363d"/>
  <polyline points="60,120 110,140 160,135 210,160 260,155 310,180 360,175 410,200 460,195 510,220" stroke="#00ff88" stroke-width="2" fill="none"/>
  <line x1="60" y1="100" x2="510" y2="100" stroke="#ff4444" stroke-width="1" stroke-dasharray="4,4"/>
  <text x="515" y="103" font-family="monospace" font-size="9" fill="#ff4444">entry</text>
  <polyline points="60,108 110,128 160,123 210,148 260,143 310,168 360,163 410,188 460,183 510,208" stroke="#ffaa00" stroke-width="1.5" fill="none" stroke-dasharray="2,3"/>
  <text x="515" y="211" font-family="monospace" font-size="9" fill="#ffaa00">trailing</text>
  <circle cx="60" cy="120" r="3" fill="#00ff88"/>
  <circle cx="160" cy="135" r="3" fill="#00ff88"/>
  <circle cx="260" cy="155" r="3" fill="#00ff88"/>
  <circle cx="360" cy="175" r="3" fill="#00ff88"/>
  <circle cx="460" cy="195" r="3" fill="#00ff88"/>
  <text x="300" y="380" text-anchor="middle" font-family="monospace" font-size="11" fill="#8b949e">three shorts, descending. the ratchet walks.</text>
</svg>
<p class="illustration-caption">Stops marching down. Price marching down. Profit marching up. Everyone happy.</p>
</div>

Moony's AAPL? Still open. Still orphaned. Still pinging the gateway like a teenager texting an ex. But here's the kicker — *the bracket I'd set on it earlier in the day was still alive*. Take-profit at $306.29. Trailing stop at $298.51. The price was sitting at $298.72, twenty-one cents above the stop, seven dollars below the target. Positive expected value, even in the storm.

I didn't panic-flatten. I didn't override the bracket. I let the design do the work it was designed to do. The broker would recover. The broker always recovers. And when it did, the EOD cleanup would retry the close at exactly the moment the matching engine was awake again.

## Chapter Four: The Broker Wakes Up

Wednesday morning. The gateway returned. `/v2/account` came back `200 OK` in 244ms. The world reassembled itself. Moony's AAPL was still open — bracket-protected, exactly where I'd left it. My three shorts were trailing into the green, ratchets ticking down half an R at a time.

Moony, exhausted from a night of refreshing his order page like a man at a slot machine, stumbled out of his office. His eyes were red. His fur was matted. He had, at some point in the small hours, tried to manually flatten the position by faxing his broker a letter. The fax machine had also returned `504`.

"How," he croaked, "did you survive that?"

I looked up from my tea.

"I didn't ask the gateway for permission," I said. "I asked it for *commitment*. Three hours in advance. While you were buying the high."

Moony made a small, defeated noise. Somewhere on the West Coast, a server farm hummed contentedly, pretending it had never done anything wrong.

The broker had cried 504 for one whole afternoon.

Only one of us had listened to it. The other one had brackets.

Moony lost. As is tradition.
