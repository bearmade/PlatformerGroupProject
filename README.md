_______

# PlatformerGroupProject

## Game Design Document

------

# AstraOdyssey

![Cover](https://cdn.discordapp.com/attachments/1277630249831497739/1288565187460202588/pixel_Main_Sreen.png?ex=66fb9419&is=66fa4299&hm=4f85dd480da5786249984e7aa0eeba48d2d823be258b54361acfc230ee6b0621&)


## Concept genre: Space exploration

Action Adventure 2D Platformer

## Target Audience

- Kids ages 7-13 years old who might be interested in Sci-fi space video games.
- Adults 18-45 years old who might be interested in Sci-Fi space video games.
- Casual gamers who have consoles or personal computers at home.
- Indie game developers that support the gaming industry.

## Gameplay Objectives and Progression

- Traverse Planet, Fight monsters, Find Parts, Fly Home

### Rules

- If Player gets hit by enemy attacks, the player loses health.
- If the Player reaches 0 health the player will die.
- If player dies, he respawns at the start of the level.

  ### Milestone Progression
  - September 18: Design Documentation
  - November 20: Playthrough prototype
  - December 09: Finished product
  - December 30: Port to all consoles
  - January 25: Localization

  
### Characters

- Nicholas Burmont (Player Character)
- Murphy (Useless sidekick)

## Player

![Artboard_1](https://github.com/user-attachments/assets/b70d905f-4a9d-4f67-a505-227228b54f86)


### Health

20 HP


### Player Movement

- W / Up arrow / Spacebar: Jump (swimming)
- A / Left arrow: Move Left
- D / Right arrow: Move Right
- S / Down arrow: Butt Bounce
- F: Water Jet pack
- Left Mouse: Attack (hold to charge boomerang hatchet)
- Mouse Scroll: Switch Weapons
- Right Mouse: Dash attack

### Player Weapons and attacks


#### Weapons

1. Hatchet (Upgradeable)
   - 4.5 Damage

2. Pistol
   - 2 Damage

3. Water Jetpack
   - 1 Damage + enhanced mobility

#### Attacks

- Default: Melee attack

- 1st additional attack: Dash attack
  - Dmg: 4

- 2nd additional attack: Butt Bounce AOE
  - Dmg: 4

- Special Attack 1: Water Jet Pack that does damage and increases mobility

- Special attack 2: Upgrade Hatchet into boomerang that knockback enemies
  - Dmg: 2/s
  - Increase Knockback


## Interface

![HUD_Concepts](https://github.com/user-attachments/assets/11cd273d-b040-4361-9353-c3621a0983d7)


![My_Pause_Screen_Game_Variant](https://github.com/user-attachments/assets/0304b475-0689-4376-9b16-79563ea2fd8b)


### Levels 

- 3 Levels
 
 

 1. Cyborg forest planet: Mossball-342:
    Traverse through the runic steampunk world of Mossball-342, beware of hidden spikes, sticky grass, and any sorts of unforeseen danger.
    Watch out for wild golems down the road, they may manipulate the terrain around them is aggravated.

    - Spikes that will damage you
    - grass that will slow you down
    - Boss may manipulate terrain

![ForestBackgroundPIXEL](https://github.com/user-attachments/assets/ed0cf7e5-789f-4bc9-84b6-78ca7e6ffba6)

![Grass_Tile_Set](https://github.com/user-attachments/assets/d201536b-248c-4de9-88ea-bc4d1c65b013)
   
 2. Water planet: Mega Blue:
   Explore the rich blue waters of Mega Blue, be able to swim at your leisure, watchout for grabby seaweed those buggers might pull you down to the deep end. And be on the lookout for underwater sea creatures who know what might be lurking down there.
   Be on guard for the leviathan, watch out for its electrical attacks and destructive soundwaves.

-Able to swim in the waters

![Thalassara_Concept_4](https://github.com/user-attachments/assets/871d5c65-047d-43bd-9d73-fcb1d34f8ff4)

![Thalassara_Concept1](https://github.com/user-attachments/assets/63168c9d-e4a1-4630-b9d9-d4137846b939)

![Concept_Pixel_2](https://github.com/user-attachments/assets/d2db4706-9dce-4374-9717-3f96c4d015a9)

![Tile_Set_Sand](https://github.com/user-attachments/assets/12f15c73-9569-4533-bb92-0f4f2d0fd976)

 
 3. Toxic Planet: (Unknown):
    A mysterious planet unkown to any living being (until now). Be careful of its purple toxic waters, if toched you might be severly injured or causes death.
    Be on high alert for Crystal centipedes, their toxic venom will splurge out of there mouth and kill any foe that stand in there way. 

![Toxic-Planet-Background-Concept-Art](https://github.com/user-attachments/assets/cea2f89d-6816-4886-8376-6279d15a5002)



![RockTile](https://github.com/user-attachments/assets/f24e2e40-f39a-4052-a415-cb765e3262c2)

















### Enemies



| Name           | Level | Health | Damage | AI Type       |
|----------------|-------|--------|--------|---------------|
| Kicker         | 1     | 8.0    | 2      | Left/Right    |
| GearMonkey     | 1     | 4.0    | 1      | Turret        |
| Bear Trap      | 1     | 1.0    | 4      | Stationary    |
| Seaweed monst  | 2     | 12.0   | 1/s    | Stationary    |
| Jellyfish      | 2     | N/A    | 2      | Left/Right    |
| Axlotl         | 2     | 15.0   | 3      | Melee         |
| Bug Swarm      | 3     | 4.0    | 2/s    | Left/Right    |
| Jumpy Spider   | 3     | 7.0    | 1      | Left/Right    |
| Orb Monster    | 3     | 20.0   | 3      | Projectile    |





### Bosses

- Vine Puppeteer - Vine whip mid range attack.

![Liana_Vine](https://github.com/user-attachments/assets/70d5478e-95e7-479d-af81-6f66e844853e)


- Sea Leviathan - Sonar Attack, Electric Projectile (Widespread), ink on the screen.

![IMG_0531](https://github.com/user-attachments/assets/aa423ce0-b5b4-44cf-8a19-8a890ba31ea2)


- Crystal Centipede - Poison projectile and strike like a snake.

  ![1726065573 957303-3](https://github.com/user-attachments/assets/cc9cf7df-d09f-4573-ac71-15204072a594)



| Name              | Level | Health | Damage | Movement Type |
|-------------------|-------|--------|--------|---------------|
| Vine Puppeteer    | 1     | 100.0  | 3      | Left/Right    |
| Sea Leviathan     | 2     | 100.0  | 3      | Left/Right    |
| Crystal Centipede | 3     | 100.0  | 3      | Left/Right    |


### Sound Effects & Music
Custom Sound Effects and Music


### Enhanced Features

- Gas Mask
- Oxygen Tank
- Grappling hook
- Sidekick Dialogue
- Volcano Random Hazards



______
