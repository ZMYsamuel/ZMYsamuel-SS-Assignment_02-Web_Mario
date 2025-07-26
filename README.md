# Web Mario
This project is developed for the "2024 Spring CS241002 Software Studio" course at National Tsing Hua University (NTHU). The goal is to create a Mario-style platformer game using Cocos Creator, closely mimicking the gameplay and appearance of the original Super Mario Bros 3.

## Scoring

| **Basic Components**           | **Score** | **Check** |
| :----------------------------: | :-------: | :-------: |
| Complete Game Process          |    5%     |    Y      |
| Basic Rules                    |   55%     |    Y      |
| Animations                     |   10%     |    Y      |
| Sound Effects                  |   10%     |    Y      |
| UI                             |   10%     |    Y      |

| **Advanced Components**        | **Score** | **Check** |
| :----------------------------: | :-------: | :-------: |
| Firebase Deploy                |    5%     |    Y      |
| Leaderboard                    |    5%     |    Y      |
| Offline Multiplayer Game       |    5%     |    N      |
| Online Multiplayer Game        |   10%     |    N      |
| Others [name of functions]     | 1-10%     |    N      |

---

## Features & Scoring Items

### Complete Game Process (5%)
- Start menu and level selection: Players can choose between Level 1 (normal difficulty) and Level 2 (same map, but with more and larger enemies).
- Game view includes game start and game over screens.
- The game process is managed according to the current game and player status.

### Basic Rules (55%)
- **World Map (10%)**: 
  - Correct physics (gravity, collision detection).
  - Background and camera follow the player.
  - At least one world map, designed to closely resemble the first stage of Super Mario Bros 3.
- **Level Design (5%)**: 
  - Static walls and interactive question blocks.
  - Hitting question blocks from below triggers an animation and either awards points or spawns a mushroom, after which the block becomes a regular tile.
- **Player (20%)**: 
  - Physics-based movement and jumping (A/D to move, Space to jump).
  - Player starts with three lives; losing a life on falling off the map or touching an enemy, with respawn at the initial position. Game over returns to the menu.
- **Enemies (15%)**: 
  - Includes flower, goomba, and fly goomba, each with correct physics and unique behaviors.
  - Only goombas can be defeated by jumping on their heads; flowers cannot be killed and must be avoided.
- **Question Blocks (5%)**: 
  - At least one type (super mushroom) that makes Mario bigger, able to jump higher, and take one extra hit.

### Animations (10%)
- Player has walking and jumping animations.
- Each enemy type has its own animation.

### Sound Effects (10%)
- Includes BGM, jump, death, power-up, game over, win, and enemy defeat sound effects.
- Sound effects do not interrupt the background music.

### UI (10%)
- Displays player lives, score, and timer.

### Appearance (10%)
- The game’s visuals are highly faithful to the original Mario, with pixelated graphics to evoke a retro feel.

### Bonus Features (up to 10%)
- **Firebase Integration (5%)**: 
  - Deployed to Firebase.
  - Membership system: Sign up, login, and save/restore game progress.
  - Real-time updates of player life, score, and coins to Firebase Realtime Database.
- **Leaderboard (5%)**: 
  - Displays the top five players’ names, scores, and emails.

---

## Summary

All required features and bonus items have been implemented, including advanced appearance and Firebase-based leaderboard. The project is expected to achieve 90% (core features) + 10% (bonus) + ?% (appearance).