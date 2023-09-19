This repository hosts the current Exoworld specifications. Discussions about design rationale and proposed changes can be brought up and discussed as issues. Solidified, agreed-upon changes to the spec can be made through pull requests.

# Exothium World: A Multidimensional Odyssey
![Exothium World Header](https://github.com/exothium/exoworld-specs/blob/main/final_landscape.png "Exothium World Header")

Dive into the thrilling realms of the Exothium World, where players embark on adventures spanning across various dimensions, reminiscent of the dynamic leagues found in Path of Exile or Runescape. 

Each dimension unfolds within a time frame dictated by a unique timer, bringing an end to that dimension's era and paving the way for the birth of a new one.

### 🌐 Game Dimensions: Constructing Realities

#### 🔢 Dimensional Blueprint

At the heart of each dimension lies a unique blueprint, a set of parameters that dictate the fundamental characteristics and rules governing that specific realm. These parameters will be the core "constructors" of each stage, weaving together the fabric of that dimension's reality.

- **Max Tiles (X)**: Defines the extent of the playable area, impacting exploration and strategy. 
- **Seed (Y)**: A unique identifier for each dimension, influencing the generation of landscapes, creatures, and resources.
- **Timespan (Z)**: Determines the lifespan of the dimension, creating a sense of urgency and driving the pace of the game.

#### 🌟 Unique Characteristics and Challenges

Each dimension is more than just a new playground; it brings with it unique characteristics and challenges that reshape the players' strategies and experiences.

- **Environmental Dynamics**: Fluctuating conditions that may affect resource availability, creature behaviors, and more.
- **Resource Dynamics**: Alterations in the distribution and abundance of resources, urging players to adapt their resource management strategies.
- **Special Events**: Unique events exclusive to a dimension, offering rare opportunities and challenges.


#### 🌱 Evolutionary Gameplay

As players traverse through different dimensions, they will notice a gradual evolution in gameplay mechanics, with newer dimensions presenting more complex and rewarding experiences.

- **Skill Progression**: Skills and abilities grow in depth and complexity, offering more strategic options as players advance.
- **Technological Advancements**: Witness the evolution of technology, with newer dimensions offering advanced tools, weapons, and more.
- **Community Interactions**: Encourage community building and collaboration through various in-game mechanics, fostering a vibrant player community.


## 🧑 Character Development
Each player will have 1 playable character (1 wallet = 1 playable character).

### 📊 Core Attributes
- **Health (HP)**: The vital life force of the character. It decreases with damage and increases with rest and healing items.
- **Stamina**: Represents the energy level of the character. Utilized in physical activities like hunting, mining, etc. Replenishes over time or with specific items.
- **Hunger**: A measure of the character's need for food. Regular eating is essential to maintain stamina and health.

### 🛠 Features
- **Inventory Space**: The capacity to carry items. Can be expanded through skills or acquiring special items, fostering strategic resource management and prioritization.

### 🌟 New Addition: Skills
- **Survival Skills**: Enhance the ability to find food, build shelters, and resist environmental hazards.
- **Combat Skills**: Develop techniques to effectively defend against and defeat enemies.
- **Craftsmanship Skills**: Improve the ability to create advanced tools, weapons, and other items.

*Note*: Incorporating a skill development system can be added to give depth and progressive element to character growth, offering players a rich and immersive experience.

## 🏞️ Environment Dynamics

### 🌌 Dimensional Characteristics
- **Lifespan**: The duration for which the dimension remains active and evolves, offering changing challenges and opportunities.
- **Map Size**: Specifies the radius of the playable area, potentially impacting strategy and exploration depth.

### 🌅 Temporal Aspects
- **Day/Night Cycle Timers**: Governs the duration of day and night phases, influencing the activities and strategies players can employ during these periods.

### 🌠 Future Developments
- **Drop Rates**: Envisioned changes to item or resource drop rates, potentially influencing gameplay strategies and resource management in upcoming dimensions.
- **Action Timers**: Planned modifications to the time required for various actions, which may alter gameplay dynamics and strategies in future dimensions.

*Note*: Keeping an eye on the future characteristics will help players anticipate and adapt to evolving gameplay elements, fostering a dynamic and engaging gaming environment.





## 🌍 Tile Characteristics

| Tile Type | Animals | Vegetation/Minerals |
|-----------|---------|---------------------|
| 🌨️ **Snow** | - Wolf: 2<br/>- Rabbits: 10<br/>- Deers: 5 | - Bushes: 20<br/>- Trees: 10<br/>- Loose stones: 5<br/>- Stone nodes: 2 |
| 🏔️ **Mountain** | - Rams: 2<br/>- Rabbits: 10<br/>- Snakes: 5 | - Bushes: 15<br/>- Loose stones: 15<br/>- Stone nodes: 4<br/>- Flint nodes: 2 |
| 🌳 **Forest** | - Bear: 2<br/>- Deers: 10<br/>- Boars: 5 | - Trees: 30<br/>- Bushes: 10<br/>- Loose stones: 5<br/>- Stone nodes: 3<br/>- Flint nodes: 1 |
| 🌾 **Plain** | - Hyenas: 2<br/>- Boars: 10<br/>- Rabbits: 5 | - Trees: 5<br/>- Bushes: 3<br/>- Loose stones: 10<br/>- Stone nodes: 3 |
| 🏜️ **Desert** | - Giant worms: 2<br/>- Snakes: 5 | - Stone nodes: 4 |
| 🌊 **Water** | - Salmon: 10<br/>- Simple fish: 30 | - (missing information) |



## 🎮 Game Actions

Each section contains the following details:
- **Requirements**: Necessary items and stats
- **Mechanics**: Action mechanics including cast time and success rate
- **Consequences**: Outcomes of the action, with potential item drops and stat changes

### 🏹 Hunting

#### Legendary Animals
- **Requirements**
  - Items: Spear, Flint Spear
  - Stats: 50 Stamina
- **Mechanics**
  - Cast Time: 4/24 of in-game daytime
  - Success Rate: 40%
- **Consequences**
  - *Success*: 
    - Meat: 2-4
    - Skin: 1
    - Exo: (missing quantity)
    - Collectables (based on type):
      - Wolf: Wolf Fur
      - Ram: Horns
      - Bear: Claw
      - Hyena: Fang
      - Giant Worm: Giant Tooth
  - *Fail*: 
    - Stats: -0/-50 HP

#### Deers/Boars
- **Requirements**
  - Items: Spear, Flint Spear
  - Stats: 35 Stamina
- **Mechanics**
  - Cast Time: 2.5/24 of in-game daytime
  - Success Rate: 75%
- **Consequences**
  - *Success*: 
    - Meat: 1-2
    - Skin: 1
  - *Fail*: 
    - Stats: -0/-30 HP

#### Rabbits/Snakes
- **Requirements**
  - Items: Spear, Flint Spear
  - Stats: 20 Stamina
- **Mechanics**
  - Cast Time: 1/24 of in-game daytime
  - Success Rate: 90%
- **Consequences**
  - *Success*: 
    - Meat: 1
    - Skin: 0-1
  - *Fail*: 
    - Stats: -0/-5 HP

### 🎣 Fishing

#### Salmon/Common Fish
- **Requirements**
  - Items: Spear, Fishing Spear
  - Stats: 10 Stamina
- **Mechanics**
  - Cast Time: 1/24 of in-game daytime
  - Success Rate: 70%
- **Consequences**
  - *Success*: 
    - Fish: 1

### 🌾 Harvest

#### Bushes
- **Requirements**
  - Items: None
  - Stats: 10 Stamina
- **Mechanics**
  - Cast Time: 1/24 of in-game daytime
  - Success Rate: 95%
- **Consequences**
  - *Success*: 
    - Berries: 1-2
    - Wood: 0-1

#### Loose Stones
- **Requirements**
  - Items: None
  - Stats: 10 Stamina
- **Mechanics**
  - Cast Time: 0.5/24 of in-game daytime
  - Success Rate: 95%
- **Consequences**
  - *Success*: 
    - Stones: 1-2

### ⛏ Mining

#### Stone Node
- **Requirements**
  - Items: Pick Axe
  - Stats: 20 Stamina
- **Mechanics**
  - Cast Time: 1/24 of in-game daytime
  - Success Rate: 90%
- **Consequences**
  - *Success*: 
    - Stones: 2-6

#### Flint Node
- **Requirements**
  - Items: Pick Axe
  - Stats: 20 Stamina
- **Mechanics**
  - Cast Time: 1/24 of in-game daytime
  - Success Rate: 90%
- **Consequences**
  - *Success*: 
    - Flint: 1-2

### 🪓 Chopping

#### Trees
- **Requirements**
  - Items: Axe
  - Stats: 20 Stamina
- **Mechanics**
  - Cast Time: 1/24 of in-game daytime
  - Success Rate: 90%
- **Consequences**
  - *Success*: 
    - Wood: 2-6

### 🍽 Eat

- **Targets**: Meat, Berries, Fish
- **Requirements**
  - Cast Time: Instant
- **Consequences**
  - HP: +0

### 💤 Sleep

- **Requirements**
  - Items: None/Sleeping Bag
  - Cast Time: 8/24 of in-game daytime
- **Consequences**
  - Stamina: +100
  - HP: -10 (null with sleeping bag stat)

### 🛠 Craft

- **Target/Requirement**: Items in inventory
- **Consequences**
  - Gains: New item
  - Loses: Items required for craft

[Crafting spreadsheet](https://docs.google.com/spreadsheets/d/1qq-7becCprjbBbyP2QPcTEjvkq-fh-fqDuUqcw7F5FY/edit#gid=0)


**Note:**
Some information is missing, such as drop rates and action timers for future dimensions, and the resources in the water tile type.

