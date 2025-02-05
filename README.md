# Ouroboros
A Rouge-like monster collector card game with a medieval alchemy theme

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
        * [] Starter monsters *3 to start, will be able to unlock more later*
- [] Battle Menu
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
        * [] Attack Direction
    * [] Effect *Place holder*
- [] Decks
- [] Battle Game Loop
    * [] Draw
    * [] Discard
    * [] Roll for first
    * [] Place Monsters
    * [] Combat
        - [] Speed Check
        - [] Speed Tie Roll
    * [] Damage
        - [] Monster defated
        - [] Damage to players
    * [] End Combat

## 0.2.0 - Aether 
- [] Player Deck Menu *See cards in current deck*
    * [] Deck sortig/building menu
- [] Out of combat game loop
    - [] Map menu
    - [] Opponents
        * [] Select Opponent
            - [] Opponent level varies
            - [] Win reward
        * [] Gold and exp multipliers


## 0.3.0 - Sulfur 
- [] Shop 3 Every 3 matches
    * [] Random inventory
        - [] Cards
        - [] Perks
        - [] Upgrades
- [] Card effects *Holographic, chrome, rainbow, negative, ect..*
- [] Card rarity
- [] Card collection log *implment more with save states later*
- [] Types advantages *ie Water x2 dameage to fire ect*
- [] Tool tips

## 0.4.0 - Salt
- [] Boss rounds *Every 10 rounds* 
    - [] New boss modifiers
- [] Legendary cards
- [] 100 round base game
- [] Card Rairity  
- [] Booster packs *7 cards, 1 effect, 6 monster (1 upgraded rarity guarenteed, 1/25 chance to have a effect)* 
    - [] Themed 
- [] Level up cards *via card sacrafice* *max level is 7* *are permanant* *can make in battle or outside* 
     Level 6 → 7: 2 cards 
     Level 5 → 6: 3 cards 
     Level 4 → 5: 3 cards 
     Level 3 → 4: 3 cards 
     Level 2 → 3: 5 cards 
     Level 1 → 2: 7 cards

     1890 cards to get one level 7 card, but power scales ^2 ie level 1 with 5 power => level 2 with power 25 
    * [] level ups bought in shop 

## 0.5.0 - Mercury
- [] Effect Tool tip
- [] Fusion Cards *Fusions can happen at special altars based on planets*  *start appearing after first boss* 
    * [] Altars
    * [] Requirements
    * [] Reagents crafting system *Recive from battles or buy from shops*
- [] Save State
    * [] persistent collection log
- [] Load Save Menu *One save with option to clear*
- [] Settings Menu 
- [] More starter monsters via unlock

## 1.0.0 - Elixir
- A cohesive story for first 100 rounds *maybe more rounds*
- [] Progessive bonus system
- [] Audio
    * [] Background Music
    * [] Combat Music4