# 🎮 Two games (and a money app), one repo

- 💰 **Financial Command Center** — a simple personal finance app: open
  [`finance.html`](finance.html) (or `/finance.html` on the GitHub Pages site).
  Track accounts (assets & liabilities), monthly cash flow, savings goals, and
  net-worth snapshots with a trend chart. All data stays in your browser's
  localStorage; JSON export/import for backups and for loading data assembled
  from your own past financial analyses.

- 🧸 **Squishopoly** — Squishmallows & Babies Monopoly for two players: open
  [`monopoly.html`](monopoly.html) (or `/monopoly.html` on the GitHub Pages site).
  Houses are **Baby Bottles 🍼**, hotels are **Cuddle Castles 🏰**, jail is the
  Playpen 🚼, money is Snuggle Bucks ₴, and the streets are Squishmallow squads
  and baby gear. Built for date night: hot-seat play, dice animations, Lullaby
  Cards 🎵, the Diaper Bag 🎒, a Nap Time pot 😴, building, mortgages, and
  bankruptcy — last spouse standing wins.
- 🌋 **Aloha Raiders II** — the shmup below, on `index.html`.

# 🌋 Aloha Raiders II — Legends of the Islands

A near-endless Raiden-style vertical shmup through Hawaiian mythology,
starring the two pilots from the photo (title-screen polaroid 📸).
Single HTML file + one photo. No build, no dependencies — open `index.html`,
or play the deployed version on GitHub Pages.

## The legend

Five mythic guardians bar the honeymoon flight, one per stage, looping
forever with rising fury (Loop 2, 3, …):

1. **Pele's Volcano** — fire goddess; spirals, eruptions, arcing lava bombs
2. **Kanaloa** — giant he'e (octopus god); tentacle streams, ink bursts, whirlpools
3. **The Night Marchers** — ghost battalion; torch curtains and spears; only the *solid* marcher takes full damage
4. **Kamapua'a** — storm boar demigod; telegraphed charges across the screen
5. **Mo'o Wahine** — serpentine dragon guardian; sweeping breath, tail bursts

Between bosses: coconut drones, tiki fleets, lunging tiger sharks, manta
squadrons, pulsing jellyfish, diving 'iwa birds, menehune war canoes,
flying-fish swarms, lava sprites, and pineapple AA turrets.

## ❤ Love Power

Grazing bullets and collecting hearts charges the LOVE meter. At 100%,
press **V** (or tap ♥) for **Aloha Overdrive**: invincibility, doubled
firepower, rainbow aura, pickup magnet, and 2× score while it lasts.

## Arsenal

- **3 weapons** via colored gems — Orchid Spread (pink), Tiki Laser
  (gold, piercing), Mana Wave (blue, heavy) — same color = power up
  (8 levels), new color = switch
- **Homing missiles** (M, 3 tiers), **menehune wingmen** (H, 2 drones),
  **Honu Shell shield** (3 hits), extra lives & bombs
- **3 themed bombs** matching your weapon: Honu Tsunami, Pele's Eruption,
  Kanaloa Vortex (converts wiped bullets into love charge)

## Gamification

- Chain combos (kills multiply score up to 4×), graze bonuses, stage
  medals (gold/silver/bronze), loop multipliers
- **12 achievements** with in-game toasts (view with **A**)
- Lifetime stats + pilot rank: Malihini → Kama'āina → Koa Warrior →
  Ali'i of the Skies → Legend of the Islands
- Hi-score, stats, config all saved in your browser

## Config (press C)

Difficulty (Chill Cruise / Classic / Pele's Wrath), music & SFX volume,
screen shake, particle density, auto-bomb on hit.

## Controls

| Action | Keyboard | Touch |
|---|---|---|
| Move | Arrows / WASD | drag |
| Focus (slow + hitbox) | Shift | — |
| Bomb | B or X | blue button |
| Love Burst | V | ♥ button |
| Pause | P | — |
| Music | M | — |

Synthesized Hawaiian slack-key/ukulele soundtrack that shifts to a tense
minor-key drum vamp during boss fights. Stage palettes cycle sunset → day →
night (stars + moon) → storm (rain + lightning) → dawn.

Debug: `index.html#boss` jumps to the boss; `#s3boss` = stage 3's boss; `#love` starts with full love.
