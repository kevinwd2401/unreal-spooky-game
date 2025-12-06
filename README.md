# Unsettler

Our Final Project! A horror game with RPG elements!

<img width="1178" height="797" alt="Screenshot 2025-12-06 141718" src="https://github.com/user-attachments/assets/183b1fed-bc60-4bc9-8b2d-cc18aa4297b2" />

## Description

The goal of this horror-themed game is to navigate through the level and reach the door to the next level. In the first level, you have to interact with the various objects in the level (left-click) and then use the inventory (I) and combining features to get the key to reach the next level. The subsequent levels don’t require keys to open the door, but you have to find the door while avoiding the monsters.

Moai Statue: It can hear your footsteps and will go to investigate, so tread carefully. Luckily, it cannot see, and it can’t chase you directly until you are pretty close.

Eye: Don’t look at it!

Mannequin: Keep it in your sight! It moves fast.

## Tasks

Kevin:
 - Use C++: For doors, light flickering/dimming, and an Interactable interface used by other blueprints
 - Sounds: The player character has footstep sounds when running forwards
 - Particles: The flickering lights have a spark particle system attached
 - NPCs with subtypes: There are 3 unique enemies with different mechanics in the game, the statue, the eye, and the mannequin, and latter two inherit from the same parent controller class as enemies that depend on the players vision
 - Materials using custom shaders: A static post-processing shader using HLSL is enabled when the player stares at the eye enemy
 - More levels: There are 3 levels total: the first is a puzzle level, the second introduces 2 enemies, and the third contains the last enemy. The maps have multiple alterations in layout, and Unreal’s modelling menu is used.

Aidan:
 - Dialogue with Branching Options
 - Inventory with UI
 - HLSL
 - Particles
 - Post Processing (Occasional eye blink, red vision on dying, nightmare jumpscare effect)
 - Inventory with Combining Items System
