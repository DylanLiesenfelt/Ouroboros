# Ouroboros
A Rougelike monster collector card game with a mideval alchemy theme

## Battle Gameplay
### Setup & Hand Management

- Both sides draw 5 cards from a deck of 50
- Players must always have 5 cards in hand
- 1 discard allowed per turn

### Battlefield

- 3 slots on each side (Left, Center, Right)
- Monster attack directions vary by card type
- After placing a monster, draw a new card

### Combat Flow

- Combat order determined by monster speed stats
    * Speed ties resolved with dice roll
    * Attacks resolved slot by slot based on speed
- Empty slot attacks deal direct damage to player health
- Match ends at 0 player health

### Effect Cards

- Can be played:

    * Before monster attacks
    * After monster attacks
    * As reactions to opponent's attacks


- Maximum 2 active effect cards at once
- Maximum 10 effect cards per deck
- Playing effect card prevents:

    * Replacing downed monsters
    * Performing sacrifice upgrades
    * and vice versa


### Sacrifice Upgrade System

- Sacrifice requirements specified on summoned card
- Sacrifices allow summoning stronger monsters from hand


## Outside of Combat Gameplay

### End of Combat Rewards:

- Gold (scales with opponent level)
- Experience Points (scales with opponent level)
- Choose 1 of 3 random cards from opponent's deck
- Exp and gold modifiers for cards left in deck and health points left

### Round Structure

- Player chooses between 3 paths:

    * Lower Level (Safer, fewer rewards)
    * Mid Level (Balanced risk/reward)
    * Higher Level (Risky, better rewards)

- Each path shows:

    * Opponent level
    * Special modifiers (buffs/debuffs)
    * Reward preview
- Difficulty increases each round

- Store appears every 3 rounds:

    * 10 Random monster cards to buy
    * 3 Effect cards to buy
    * 3 Card Upgrades to buy
    * Special offers for perfect round streaks
    

### Milestone Battles

- Boss battle every 10 rounds:

    * Guaranteed uncommon+ card drop
    * Special boss modifiers
    * Unique boss-only cards to collect

### Game Progression
    - Base game ends at round 100
    - Endless mode

## Game Start

- Player selects 3 base monsters to build their starting deck around

    * First playthrough starts with base 3 monster choices
    * Additional monster choices unlock through:

        - Completing rounds
        - Defeating specific bosses
        - Achieving certain milestones

## Road Map
### 0.1.0 - Flask
- [] Start Menu
    - [] Temp base card select menu
- [] Play Area
    * [] Hand Area
    * [] Deck Area
    * [] Discard Area
    * [] Health Display
    * [] Battle field
        - [] Moster Slots
        - [] Effect Slots
- [] Test Cards
    * [] Monster
        * [] Type
        * [] Stats
            - [] Speed
            - [] Attack
            - [] Defense
            - [] Health
        * Attack Direction
    * [] Effect 
- [] Decks
- [] Battle Game Loop
    * [] Draw
    * [] Discard
    * [] Roll for first
    * [] Place
    * [] Combat
    * [] Damage
    * [] End Combat

## 0.2.0 - Aether 
- [] Starter Deck *1 to start*
- [] Player Deck Menu
- [] Game Loop
- [] Opponents

## 0.1.0 - Sulfur 
- [] Core Combat Mechanics
    * [] Turns
    * [] Health
    * [] Damage
    * [] Types advantages

## 0.0.4
- [] Rounds
- [] Oppnent Types
- [] Opponent Reward
- [] Round Reward/ PRogress

## 0.0.5
- [] Card Effects *holo, chrome, negative, ect..*
- [] Effect Tool tip
- [] Card Rairity  
- [] Merge/Level up cards *Still figuring out how I want to do this*

## 0.0.6
- [] Save State
- [] Load Save Menu *One save with option to clear*
- [] Settings Menu *Temp* 


## 1.0.0 - Elixir
- [] Progessive bonus system
- [] Active run card sorting system *to help build decks*
- [] Card Collection Menu
- [] Audio
    * [] Background Music
    * [] Combat Music

## Idea Pool
- Crafting System
