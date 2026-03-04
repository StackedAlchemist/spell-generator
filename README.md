# ✨ Arcane Spell Generator

> *"Speak the words. Shape the magic. Cast what has never been cast before."*

A randomized spell-casting engine that conjures unique arcane spells on demand. Every cast produces a new combination of spell name, element, effect, range, and incantation — no two spells are ever the same.

**[🔮 Cast a Spell](https://stackedalchemist.github.io/stacked-alchemist/spell-generator/)**

---

## ✦ Features

- **Randomized Spell Generation** — Combines spell schools, elements, effects, ranges, and casting words into unique spells
- **Spell Cards** — Each generated spell displays as a styled arcane card with all attributes
- **Incantation System** — Generates a unique spoken incantation for each spell
- **Rarity Tiers** — Spells are assigned rarity levels (Common through Legendary)
- **Instant Recast** — Generate new spells instantly with a single click
- **Fully Animated** — Particle effects and glow animations on cast

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Arcane card styling, animations, particle effects |
| Vanilla JavaScript | Randomization engine, spell assembly logic |

---

## 🚀 Running Locally

```bash
git clone https://github.com/StackedAlchemist/stacked-alchemist.git
cd Portfolio/spell-generator
# Open index.html in your browser
```

No dependencies, no build tools, no API keys required.

---

## 📁 File Structure

```
spell-generator/
├── index.html    # App markup
├── styles.css    # Arcane theme and animations
└── script.js     # Spell generation engine
```

---

## 🔮 How the Generator Works

The engine pulls from multiple word banks and combines them using weighted randomization:

- **School** — Evocation, Conjuration, Illusion, Necromancy, Transmutation, etc.
- **Element** — Fire, Ice, Shadow, Lightning, Arcane, Nature, etc.
- **Effect** — Damage, Heal, Bind, Reveal, Transform, Summon, etc.
- **Range** — Touch, Close, Medium, Long, Global
- **Rarity** — Weighted probability favoring Common, with Legendary being rare

---

*Built by [Billy Williams](https://stackedalchemist.github.io/stacked-alchemist/) — Stacked Alchemist*
