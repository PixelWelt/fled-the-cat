# Fled the Cat – Game Design Document

## 1. Project Overview

**Project Name:** Fled the Cat  
**Genre:** Timed Survival Puzzle  
**Target Audience:** Casual gamers, animal lovers, allergy sufferers, and fans of cute aesthetics and meme culture  
**Target Age Rating:** USK 6 (intended)

### 1.1 Game Concept

The player takes on the role of a cat-allergic person trying to survive in a household full of cats, find specific items, and escape the apartment.

The cats are the main enemies. Their proximity and contact with cat hair trigger allergic reactions, gradually reducing the player's health and putting them under constant time pressure.

The game combines humorous situations with survival and puzzle elements. Players must find items, overcome obstacles, avoid cats, and reach the exit as quickly as possible.

## 2. Unique Selling Points (USP)

- **Allergy Awareness with Humor:** An exaggerated and humorous representation of life as a cat-allergic person.
- **Meme Potential:** Absurd situations, funny animations, and exaggerated reactions to cats.
- **Cute Art Style:** Adorable cats and a cartoon-style world contrast with the player's increasingly desperate survival situation.
- **Challenge and Competition:** High scores and leaderboards encourage players to improve their escape times and overall performance.

## 3. Player Experience and Perspective

The player experiences the game world from the perspective of a cat-allergic person.

The setting is a shared apartment or house inhabited by several cats. The environment is an exaggerated, cartoon-style representation of an everyday household.

The intended player experience should be:

- Humorous and entertaining.
- Challenging through time pressure and limited health.
- Encouraging exploration through hidden items and alternative routes.
- Providing replayability through scoreboards and high scores.

**Perspective:** Not yet finalized. Third-person is one possible option.

## 4. Visual and Audio Style

- Cute, cartoon-style graphics.
- Smooth animations and movement.
- No overly detailed or realistic graphics.
- Contrast between the cute visual style and the chaotic survival situation.
- Use of Kelly Assets.
- Humorous sound effects and fitting background music.

## 5. Game World and Fiction

**Setting:** Shared apartment, flat, or house.

The game world contains:

- Cats as the main enemies.
- Typical household objects and furniture.
- Hidden and collectible items.
- Multiple rooms and possible escape routes.
- Easter eggs and hidden cat references.

The environment should function both as a playable space and as a puzzle.

### 5.1 The Three Cats

There are three distinct cat types, each with different characteristics and gameplay implications.

| Cat | Characteristics | Gameplay Role |
|---|---|---|
| **Fled** | Fast-moving cat | Difficult to outrun and avoid due to its speed |
| **Flat** | Hard to spot and good at hiding | Creates surprise encounters and requires careful exploration |
| **Fat** | Slow-moving but large and heavy | Causes the highest allergic reaction and deals the most damage |

Each cat type introduces a different kind of threat, requiring the player to adapt their movement and escape strategy.

## 6. Core Gameplay Loop

The basic gameplay loop:

1. The player starts in a household full of cats.
2. They explore the environment and search for required items.
3. Cats and their proximity trigger allergic reactions.
4. The player's health gradually decreases due to allergic exposure.
5. The player uses items, overcomes obstacles, and finds an escape route.
6. The objective is to reach the exit before health is completely depleted.
7. Upon death, a humorous hospital / EpiPen animation is triggered.
8. The player starts a new run.

**Key Design Decision:** There are no checkpoints initially. Every run starts from the beginning.

## 7. Objectives and Progression

### 7.1 Short-Term Goals

- Stay alive and avoid allergic reactions.
- Avoid cats whenever possible.
- Find collectibles and required items.
- Choose the most efficient escape route.
- Complete sub-objectives to unlock the escape route.

Example: The player must find a lost key to unlock a door. Cat food can be placed to distract cats and buy some time.

### 7.2 Long-Term Goal

The overall objective is to reach the exit and escape the household.

### 7.3 Replayability

- High scores and leaderboards.
- Improving personal best escape times.
- Different routes and possible solutions.
- Optional collectibles and Easter eggs.

## 8. Game Systems and Mechanics

### 8.1 Movement

- WASD controls.
- Fast and responsive movement.
- Physics-based interactions and humorous movement mechanics.

### 8.2 Interaction

- Items are automatically picked up by walking over them.
- Items can be used by pressing designated keys.
- Additional interactions with the environment are possible.

### 8.3 Health and Allergies

The player's health is affected by their cat allergy.

Potential mechanics:

- Proximity to cats reduces the player's health.
- Cat hair and other allergen sources can introduce additional hazards.
- The intensity of allergic reactions may depend on distance and exposure duration.
- Different cat types cause different levels of allergic damage.
- Fat causes the highest allergic reaction, while Fled and Flat introduce different challenges through their speed and hiding abilities.
- When health reaches zero, the player dies and the run ends.

The exact implementation and balancing of the allergy mechanics still need to be defined.

### 8.4 Items and Collectibles

Items serve different purposes:

- Keys and quest items to unlock paths.
- Tools and consumables to handle dangerous situations.
- Optional collectibles for additional points.
- Cat food to distract cats and temporarily create opportunities to move past them.

## 9. Technology and Development Environment

**Game Engine:** Godot

**Development Tools:**
- Visual Studio Code
- Git / GitHub

**Development Platforms:**
- macOS
- Ubuntu
- Arch Linux

## 10. Ideas and Potential Extensions

The following features are possible extensions but are not necessarily part of the initial game scope:

- Third-person perspective.
- Multiplayer mode.
- Additional levels and households.
- More cat types with unique behaviors.
- Additional allergy symptoms and items.
- Easter eggs and hidden cat references.
- Extended leaderboards and statistics.

## 11. Open Questions

Unresolved design decisions and technical questions are collected here. Once a question has been answered, it will be moved to the "Resolved Questions" section along with a short explanation of the decision.

- How exactly should the allergy mechanics work (range, damage, intensity)?
- What specific movement and behavior patterns should each cat have?
- How many cats and rooms should each level contain?
- Which items are required to escape?
- How should the scoreboard be calculated?
- Which perspective will be used in the final game?
- How prominent should physics-based interactions be?

## 12. Resolved Questions

Design decisions made so far:

- **Enemy Concept:** Cats are the main enemies. Their proximity triggers allergic reactions and reduces the player's health.
- **Cat Types:** Three distinct cats are planned: Fled (fast), Flat (hard to spot and hiding), and Fat (slow but causes the highest allergic damage).
- **Checkpoints:** No checkpoints are planned for the initial version. Every run restarts after a Game Over.

## 13. Current Development Status

The project is currently in the concept and planning phase.

The core game idea, genre, and main gameplay elements have been defined. The specific implementation of the game mechanics, particularly the allergy and enemy systems, still needs to be developed and tested through prototyping.

The next step is to build a playable prototype featuring basic movement, the three cat types, and an initial implementation of the health system.

## 14. Known Bugs

No known bugs have been documented so far.