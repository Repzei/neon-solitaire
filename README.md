# ♠♥♦♣ NEON SOLITAIRE ∞ VOID EDITION

Klondike solitaire with too much neon. **One file, zero dependencies, no build step.**

🎮 **Play it → https://repzei.github.io/neon-solitaire/**

## Controls

| Input | Action |
|---|---|
| Drag a card | Move it (or a whole face-up run) |
| Tap card → tap destination | Same thing, without dragging |
| Double-tap | Send straight to a foundation |
| `Space` | Draw from the stock |
| `N` / `U` / `H` / `A` / `P` | New · Undo · Hint · Auto-finish · Pause |
| `Esc` | Deselect |

## Features

- Draw 1 or Draw 3 (toggle in the header)
- Full-state undo, hints, double-tap to foundation
- ⚡ Auto-finish — and it **starts itself** once it can *prove* the win is already
  in the bag (it dry-runs the whole rest of the game on a copy of the position first)
- **Pause** freezes the clock, the input, the animations *and* the particle field
- Score with a combo multiplier, timer, best time (localStorage)
- WebAudio synth sound — no audio files
- Physics + fireworks win sequence
- Four-colour accessible deck: warm family (♥♦) vs cool family (♠♣), no green
- Keyboard, mouse, touch — responsive from phone to ultra-wide

## Running locally

Open `index.html` in a browser. That's it.

## Deploying

GitHub Pages serves `index.html` from the `main` branch.
