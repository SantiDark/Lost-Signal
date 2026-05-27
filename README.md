# SIGNAL LOST

A short psychological narrative game. Playable in browser. No install required.

**[▶ Play on itch.io](YOUR_ITCH_LINK)**

---

## About

You are Dr. Mara Chen — Division 7 Crisis Negotiator. You have been sent to talk a man
named Thomas Kael down from a rooftop. As you speak with him, he tells you what was done
to his life, and who signed the paperwork. Your name is on the file.

SIGNAL LOST is a narrative systems game about institutional gaslighting, the reliability
of memory, and what it means to believe someone inside a system designed to make belief
impossible.

---

## How to run

Open `signal_lost.html` in any modern browser. No server, no build step, no dependencies.

```bash
# That's it:
open signal_lost.html
```

Or host it anywhere that serves static HTML — GitHub Pages, itch.io, Netlify.

---

## Systems

### Cognitive Reliability meter
Tracks your psychological state across the conversation. Drops when you dismiss
evidence, receive contradictions, or hear things your memory can't account for.
At low values: the scene degrades visually, and a fourth category of darker choices
unlocks. Below 35% with the right flags: the fourth ending becomes reachable.

### Evidence desk
Objects appear on a desk to the right as the scene develops. Picking them up and
reading them unlocks dialogue options that directly reference what you just read.
The batch sign-off log. The Vantex personnel record. Elisa Park's letter.
The list of seventeen names, ten of them redacted by auto-moderation.

### Action choices
Mixed in with dialogue are physical choices: step closer to the ledge, sit beside him,
reach for your radio, grab his wrist. Each has mechanical and narrative consequences.
The grab action is marked dangerous and carries the highest reliability penalty in the
game. It also produces one of the most interesting endings.

### 9 endings
Routed by accumulated flags, not just the final question. The ending you get reflects
the full texture of how you played — whether you read the documents, which actions you
took, whether you disclosed the signature on the radio, and where your reliability
landed.

---

## Technical

| Property | Value |
|---|---|
| Engine | Vanilla HTML/CSS/JS — zero dependencies |
| Audio | Web Audio API — procedural drone, rain, tension pulse, chimes |
| Visuals | Canvas 2D — procedural city skyline, rooftop, weather, glitch |
| Font | Courier Prime (mono) + Crimson Pro (body) |
| File size | ~65KB |
| Browser support | All modern browsers |

---

## Endings reference

| Ending | Title | Condition |
|---|---|---|
| 1 | WITNESS | Believed Thomas |
| 2 | SIDE BY SIDE | Believed + sat on ledge |
| 3 | PAPER TRAIL | Believed + read batch log + confronted with it |
| 4 | OPERATOR | Professional distance |
| 5 | FLAGGED | Kept distance + disclosed to radio |
| 6 | STATIC | Chose uncertainty throughout |
| 7 | TRUE BELIEVER | Believed + grabbed his wrist |
| 8 | SECURED | Grabbed without believing |
| 9 | SIGNAL LOST | Fractured response + reliability < 35 |

---

## Portfolio context

Built as a portfolio piece demonstrating:
- **Narrative systems design** — choices feed a live mechanical state that changes
  what options are available, not just what happens
- **Mechanic-as-theme** — the Reliability meter mirrors the game's subject matter;
  gaslighting works by eroding your confidence in your own memory
- **Document-gated dialogue** — reading evidence unlocks specific responses,
  rewarding exploration without punishing non-exploration
- **Procedural audiovisual** — no assets; everything rendered in real time from code

---

*"The system shows what the system shows."*
