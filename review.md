# Game Basic Information #

## Summary ##

KnightQuest is a 2D platformer with simple sword combat mechanics. The goal of the game is to traverse various obstacles and platforms while attacking or avoiding various enemies. The level begins relatively straightforwardly, but increases in difficulty the further you progress in the map. The map's platforming will grow more difficult to complete, while variations to the slime enemies will make avoiding or defeating them more challenging as well. Through the map, the player will encounter deadly spikes both static and falling, disappearing platforms, exploding enemies, and moving platforms. The player wins when the finally reach the end of the level and save the captured royal family.

## Gameplay Explanation ##

**In this section, explain how the game should be played. Treat this as a manual within a game. It is encouraged to explain the button mappings and the most optimal gameplay strategy.**

Gameplay in KnightQuest revolves around moving or jumping to traverse obstacles or avoid enemies, as well as attacking. The A and D keys are used to move left and right respectively, while the spacebar allows the player to jump. Pressing spacebar again after having jumped allows the player to jump one more time before landing. Pressing the left mouse button for fewer than 2 seconds will perform an attack, while holding for 2 or more seconds will perform a heavy attack. Pressing E performs a spin attack. When the player touches a slime, they will take damage, indicated to the player by a reduction of their health bar. Players may encounter chests that restore health when stood on. Platforming generally requires good timing to ensure that the player does not land on an enemy or fall off a platform. At certain point, players will reach checkpoints that will update where they spawn on death. 


**If you did work that should be factored in to your grade that does not fit easily into the proscribed roles, add it here! Please include links to resources and descriptions of game-related material that does not fit into roles here.**

# Main Roles #

Your goal is to relate the work of your role and sub-role in terms of the content of the course. Please look at the role sections below for specific instructions for each role.

Below is a template for you to highlight items of your work. These provide the evidence needed for your work to be evaluated. Try to have at least 4 such descriptions. They will be assessed on the quality of the underlying system and how they are linked to course content. 

*Short Description* - Long description of your work item that includes how it is relevant to topics discussed in class. [link to evidence in your repository](https://github.com/dr-jam/ECS189L/edit/project-description/ProjectDocumentTemplate.md)

Here is an example:  
*Procedural Terrain* - The background of the game consists of procedurally-generated terrain that is produced with Perlin noise. This terrain can be modified by the game at run-time via a call to its script methods. The intent is to allow the player to modify the terrain. This system is based on the component design pattern and the procedural content generation portions of the course. [The PCG terrain generation script](https://github.com/dr-jam/CameraControlExercise/blob/513b927e87fc686fe627bf7d4ff6ff841cf34e9f/Obscura/Assets/Scripts/TerrainGenerator.cs#L6).

You should replay any **bold text** with your relevant information. Liberally use the template when necessary and appropriate.

## User Interface

**Describe your user interface and how it relates to gameplay. This can be done via the template.**

The user interface is designed based on the core game logic and any information we believe is necessary for the player to have when challenging the Demon King. There are four scenes, three of which are for purposes of the user interface only. Any buttons or interactables in the UI have simple shadows when hovered or clicked to provide feedback to the player, letting them know a button is interactable or that they have successfully clicked the button. All user interfaces were tested for any major discrepancies between differing monitor specs and should display properly for all aspect ratios and resolutions.

The user interface is designed based on the core game logic and giving necessary information to provide better user experience for the players. Our game is a platform game and providing these five scenes helps the players to interact to the game itself.
<img width="532" alt="Screen Shot 2022-06-06 at 1 34 51 AM" src="https://user-images.githubusercontent.com/58205103/172125964-93db4ae1-5b5d-4386-8274-509bfdaf82f8.png">

- Easy Scene - This Scene provides "Easy Difficulty" gameplay where their less enemies and the enemies are weaker.
- Ending Scene - This Scene provides "Ending Menu Scene" where it asks the player to play again or go back to the main menu. 
- Hard Scene - This Scene provides "Hard Difficulty" gameplay where their more enemies and the enemies are stronger than "Medium Difficulty".
- MainMenu Scene -  This Scene
- Medium Scene - This Scene provides "Medium Difficulty" gameplay where their more enemies and the enemies are stronger than "Easy Difficulty".

[HealthBarUi](https://user-images.githubusercontent.com/58205103/172116292-bb675fba-2b91-49e9-b82a-311701dba67a.png) - The HealthBar UI is anchored to the top left of the screen to adjust to any resolution, as well as communicate with the player how big is the damage that is taken from the enemy. The HealthBar of the player is set into 100 HP. The Player will be taken damage if the enemy collided onto the player. Health is checked on every update and the UI is updated accordingly. [Health Update code here](https://github.com/breliu-dv/KnightQuest/blob/37519690f1b5ff7f8343d983feb7f3d123c4764d/Assets/Scripts/KnightController.cs#L369)





## Movement/Physics

**Describe the basics of movement and physics in your game. Is it the standard physics model? What did you change or modify? Did you make your movement scripts that do not use the physics system?**

## Animation and Visuals

**List your assets including their sources and licenses.**

**Describe how your work intersects with game feel, graphic design, and world-building. Include your visual style guide if one exists.**

## Input

**Describe the default input configuration.**

**Add an entry for each platform or input style your project supports.**

## Game Logic

**Document what game states and game data you managed and what design patterns you used to complete your task.**

## Producer



# Sub-Roles

## Audio

**List your assets including their sources and licenses.**

**Describe the implementation of your audio system.**

**Document the sound style.** 

## Gameplay Testing

**Add a link to the full results of your gameplay tests.**

**Summarize the key findings from your gameplay tests.**

## MapLevel and Narrative Design

**Document how the narrative is present in the game via assets, gameplay systems, and gameplay.** 
<img width="935" alt="Screen Shot 2022-06-06 at 1 50 24 AM" src="https://user-images.githubusercontent.com/58205103/172128787-217d852f-a624-4d46-a84b-ca800c25e25d.png">


- This map level design starts with a very simple spike trap on the **first layer of the cave** and there are only two slime enemies. As you go deeper into the **second layer of the cave**, you notice there are more green slime enemies that is been spawn and spawning more traps and introduce new trap called "the raining spikes". Once you reach out to the **purple layer of the cave**, 


## Press Kit and Trailer

**Include links to your presskit materials and trailer.**

**Describe how you showcased your work. How did you choose what to show in the trailer? Why did you choose your screenshots?**

## Game Feel

**Document what you added to and how you tweaked your game to improve its game feel.**

## Cross Platform
