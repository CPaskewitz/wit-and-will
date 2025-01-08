# **Wit and Will**

## **Overview**
**Wit and Will** is a strategic tactical RPG (TRPG) where players test their skills in resource management, class countering, and decision-making. Inspired by the mechanics of **Black and White II**, the game blends elements of turn-based strategy and real-time competition.

Players face off in either **Versus AI** or **Versus Player** modes, spending their limited Resource Points (RP) strategically across 9 rounds to secure victory. Class choices, abilities, and equipment play a crucial role in determining the outcome of each match.

---

## **Features**
- **Turn-Based Gameplay**: Battle through 9 intense rounds, allocating RP to boost stats, activate abilities, or equip items.
- **Dynamic Class System**:
  - **Warrior**: The tank, excelling in defense and sustained attacks.
  - **Mage**: A glass cannon with devastating spells.
  - **Rogue**: Agile and precise, relying on speed and critical strikes.
  - **Cleric**: A balanced fighter with defensive and supportive capabilities.
- **Real-Time Multiplayer (Versus Player)**: Compete against other players using Partykit for live communication.
- **Single-Player (Versus AI)**: Challenge the AI, which adapts to your strategy.
- **ELO Ranking System**: Matchmaking ensures competitive games by pairing players of similar skill levels.

---

## **Game Mechanics**
1. **Resource Points (RP)**:
   - Players start with **99 RP**, shared across all 9 rounds.
   - RP is spent on boosting stats, activating abilities, or equipping items.
   - Strategic RP management is key to victory.

2. **Class Counter System**:
   - **Warrior > Rogue > Cleric > Mage > Warrior**
   - Each class has strengths, weaknesses, and even matchups.

3. **Abilities and Equipment**:
   - Customize your strategy with unique abilities and equipment for each class.
   - Abilities cost RP and provide temporary bonuses or effects.
   - Equipment costs RP and provides permanent stat boosts.

4. **Win Conditions**:
   - The player with the most round victories after 9 rounds wins.
   - In case of a tie, the winner is determined by remaining RP.

---

## **Technology Stack**
- **Frontend**: Next.js (TypeScript)
- **Backend**:
  - **Partykit**: Real-time multiplayer communication.
  - **Convex**: Database for persistent player stats, game history, and leaderboards.
- **Authentication**: Clerk for secure user management.
- **ELO Ranking**: Dynamic matchmaking based on skill level.

---

## **How to Play**
1. **Versus AI**:
   - Choose your class and allocate RP to outsmart the AI.
   - Adapt as the AI counters your strategy.

2. **Versus Player**:
   - Matchmake against players of similar skill level.
   - Choose your class each round and react to your opponent's decisions in real-time.

3. **Victory**:
   - Win more rounds than your opponent or strategically conserve RP to break ties.