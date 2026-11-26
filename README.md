# Starhop

A one-button space game. Orbit a planet, launch at the right moment, and hop from world to world before each one collapses.

**Play:** https://orencohen211.github.io/starhop/

## How to play
- Tap, click or press **Space** to leave orbit. You fly off along the dotted aiming line.
- Fly into another planet's ring to be caught by its gravity.
- Each planet starts collapsing once you're on it, so don't wait too long.
- Skip over a planet for bonus points. Every landing earns a star.

## Features
- **Endless mode** with wormholes, black holes, asteroid belts, bumpers and glass planets.
- **20 missions** in two packs, each rated up to 3 stars (clear, beat par, no close calls).
- **Store** with trails, ships, upgrades, power-ups, planet themes, and launch and landing effects.
- **Accounts**: sign up with email and a unique callsign, log in on any device, reset your password by email.
- **Cloud saves and a global leaderboard** (Firebase Authentication + Firestore). Guests can still play; their progress is saved in the browser.

## Development
The whole game is a single self-contained file, `index.html`, with no build step. Open it in a browser to play locally.

Accounts use Firebase (project `starhop-79786`). The database security rules live in `firestore.rules`; after changing them, paste them into Firebase console → Firestore Database → Rules and publish.
