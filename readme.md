# SillyGames 🎮

A personal arcade — browser games built with Claude, hosted on Vercel.

## Games

| Game | Genre | Path |
|------|-------|------|
| Pigs vs Robots | Tower Defense | `games/pigs-vs-robots/index.html` |
| Beastman RPG | RPG | `games/beastman-rpg/index.html` |

## Structure

```
SillyGames/
├── index.html                      ← Homepage / game select screen
└── games/
    ├── pigs-vs-robots/
    │   └── index.html              ← Paste full game HTML here
    └── beastman-rpg/
        └── index.html              ← Paste full game HTML here
```

## Adding a new game

1. Create a new folder under `games/`
2. Drop your self-contained `index.html` in it
3. Add a card to the homepage `index.html`
4. Push to GitHub → Vercel auto-deploys

## Deploy

Connected to Vercel. Every push to `main` auto-deploys.