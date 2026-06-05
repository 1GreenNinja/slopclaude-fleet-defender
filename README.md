# SLOPCLAUDE — Fleet Defender

A single-file HTML5 canvas arcade shooter. Fly a fighter over a starlit sunset sea,
blast incoming ships, grab power-ups, and take down the glossy Star-Trek-style
**Dreadnought** boss to win. No build step, no dependencies — just open `index.html`.

![Fleet Defender](https://img.shields.io/badge/play-in%20browser-2fd3c6)

## Play

Open `index.html` in any modern browser, then **click "Launch"** (the click is also
what unlocks audio). Or play the hosted version via GitHub Pages once enabled.

## Controls

| Action | Keys |
| --- | --- |
| Aim | Move the **mouse** (the nose tracks the cursor) |
| Move | **WASD** — relative to your aim: `W` forward · `S` reverse · `A/D` strafe |
| Fly  | **← →** bank the nose · **↑ ↓** thrust fore/aft |
| Fire | **Click** or **Space** (hold for continuous) |
| Bomb | **B** — screen-clearing blast (also grants brief invulnerability) |

## Features

- **Scrolling world** (Defender-style): a four-screen-wide procedurally generated
  landscape that scrolls with parallax as you fly to the edges.
- **Landing bases:** flat mesas carved into the ridge with lit decks and beacons —
  set down on one to **resupply** (refill bombs, repair hull, restock your gun).
- **Parallax starfield** with twinkling layers, shooting stars, a nebula band, a
  procedural mountain ridge, and a rippling lake reflection.
- **Weapons** that drop from heavy ships and persist until you're hit:
  Twin · Spread · Plasma (triple damage).
- **Power-ups:** 🛡 Shield (45s impervious) · ✦ Triple-shot · ⚡ Rapid-fire · ✚ Repair · 💣 Bomb.
- **Fractional health** — regular enemy fire chips ¼ of a heart (⅛ on a glancing hit);
  hearts stack with no cap, and you earn a bonus life every 500 points.
- **Boss fight:** a shiny Federation-style Dreadnought with a glowing blue reactor core,
  twin warp nacelles with warp trails, player-tracking phaser turrets, a deflector dish,
  and slow, dodgeable bullet patterns. Beat it and **you win**.
- **Synthesized sound** — every effect is generated live with the Web Audio API (no files).

## Tech

Pure vanilla JavaScript + Canvas 2D in one HTML file. ~1k lines, zero dependencies.

---

Built interactively with Claude Code. 🚀
