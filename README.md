# VibeLingo
A web multiplayer game that combines aerial dogfighting with language-learning.

## Overview
"Vibelingo" is a 3D multiplayer web game where players take on the roles of student witches or wizards riding broomsticks, soaring through the enchanting "Lingo Bay." Surrounded by forests, mountains, and whimsical sights like mini-islands, sea monsters, merpeople, and dragons, players compete to collect pixies, cast spells using foreign words, and outwit opponents in fast-paced aerial combat. The game blends action with language-learning mechanics, offering a mix of open-world chaos, structured lobbies, and bot matches.

## Core Mechanics
1. **Player Characters:**
   - Players choose between *student witch* or *student wizard* models (premium models available with membership).
   - *Characters spawn on the ground after completing a captcha and selecting a name and model.*
   - *Launch sequence: Players pass two portals while lifting off (multiplayer lobby or private/bot lobby).*

2. **Flight and Movement:**
   - Players fly on broomsticks around Vibelingo Bay.
   - Pixies grant speed boosts to enhance mobility.

3. **Pixie Collection:**
   - Pixies are scattered across the bay.
   - Types:
     - *Word Pixies:* Add a random foreign word to the player’s spell ammunition.
     - *Speed Pixies:* Temporarily boost flight speed.
     - *Health Pixies:* Restore player health.

4. **Combat System:**
   - Players cast spells by "firing" foreign words from their pixie-collected inventory at opponents, with an *optional player-activated targeting system*.
     - Targeting (when activated) locks onto the most viable target (e.g., closest or weakest opponent).
     - Players can cycle between available targets manually.
     - Without targeting, spells are cast freely in the direction of flight.
   - When hit, the attacked player sees a multiple-choice prompt (up to 5 options) to translate the word, drawn from the attacker’s inventory.
   - Correct translation in time = spell deflected; incorrect or timeout = health loss.

5. **Game Modes:**
   - *Open World:* Unlimited players, free-for-all, 3-minute rounds with resets (health, scores, inventory).
   - *Multiplayer Lobby (Portal 1):* Up to 8 players, 3-minute rounds.
   - *Private/Bot Lobby (Portal 2):* Closed match vs. bots, unique invite code for friends.

6. **Progression and Premium Features:**
   - Free players: Basic models, standard modes.
   - Premium membership: Sign-in, progress tracking, premium models, exclusive modes/customization.

7. **User Interface:**
   - Introductory overlay explains gameplay.
   - In-game chat (toggle on/off).
   - Health bar, pixie inventory, optional targeting UI, and score display.

## Setting
- **Lingo Bay:** A fantasy bay with a vibrant horizon—forests, mountains, mini-islands, and distant creatures (sea monsters, merpeople, dragons). The aesthetic is whimsical and immersive, encouraging exploration.

## Goals
- Collect pixies to build spell ammunition and survive.
- Outlast and outscore opponents by mastering word-based combat, with or without targeting.
- Explore Vibelingo Bay and enjoy its curiosities.

## Notes
- Rounds reset every 3 minutes to keep gameplay fast and dynamic.
- The captcha ensures fair entry, preventing bots.
- Balance pixie spawn rates to avoid overwhelming players.
- Targeting system is optional for player preference—free aiming should still be viable.
