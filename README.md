# 🌸 Bloom — one tap, endless chains

**One tap sets off a cascade of light.** Drop a pulse, catch a drifting orb, and
watch it *bloom* into a ring that catches more orbs — chaining across the whole
screen. The longer the chain, the bigger the score. Simple to start, impossible
to put down.

👉 **Play free:** https://rahulatrkm.github.io/bloom/

## The twist nobody else has

Bloom isn't just a chain reaction — **every orb color chains differently**, so
each tap triggers a different, emergent firework:

| Color | Behavior |
|-------|----------|
| 🩵 **Cyan** | A steady, reliable bloom |
| 💗 **Magenta** | Bursts extra wide — great for crowds |
| 💛 **Gold** | Lingers longer — catches slow drifters |
| 💚 **Green** | Splits into a second bloom — chaos multiplier |
| 🧡 **Bomb** *(rare)* | Detonates a huge blast + score bonus |
| 💜 **Void** *(rare)* | A black hole that pulls nearby orbs in |

Reading the board and choosing *where* to tap so the colors cascade into each
other is the whole game — easy to learn, endlessly deep.

## Three ways to play

- 🌊 **Waves** — one pulse per wave. Hit the target or bust. Ramps fast.
- ♾️ **Endless** — a recharging pulse meter; chase the highest score you can.
- 🧘 **Zen** — no fail state, no pressure. Just make light.

## Why it's addictive

- **One input.** Tap anywhere. That's the whole control scheme.
- **Juice everywhere** — glowing rings, particle bursts, floating score,
  screen-shake, combo call-outs, and satisfying WebAudio blips that rise in pitch
  as your chain grows (mute anytime).
- **"One more go" loop** — instant restart, per-mode high scores, chain bonuses
  that reward big risky taps.
- **Share your score** — game over generates a slick score card you can share
  (native share sheet on mobile, or saved image + copied link on desktop).
- **Runs anywhere** — a single `index.html`, no dependencies, works offline,
  scales to any phone or desktop screen.

## Free — for now

Bloom is **free to play, all day and all night**. Play, share it, get hooked.

## How to play

1. **Tap anywhere** to drop a pulse.
2. Any orb the pulse touches **blooms** into its own ring.
3. That ring catches more orbs → they bloom too → **chain reaction**.
4. Longer chains score exponentially. Big chains pay a bonus.
5. In Waves, you get **one pulse** — make it count. In Endless, watch your
   energy meter. In Zen, just enjoy.

**Controls:** tap / click anywhere · `Space` drops a pulse at the cursor ·
`P` or `Esc` to pause.

## Tech

A single self-contained `index.html` — HTML5 Canvas + vanilla JavaScript, no
build step, no dependencies, no tracking. Physics-lite orb drift, a phase-based
bloom lifecycle (grow → hold → shrink) with per-color tuning, particle system,
and a tiny WebAudio synth for feedback. High scores persist in `localStorage`.

## License

MIT — see [LICENSE](LICENSE).
