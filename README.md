# GDIM32 In Class Activities

# W1

### Activity 1

To ace the class, my tablemates discussed that we should attend LA hours and actively search online for answers to code issues or for coding specific things tutorials.

### Activity 2

1: 10

2: 2

3: write "hello world" to the console every frane.

4: MonoBehaviour

5: Print "x=10" to the Console upon game load.

6: Method argument and method parameter, which are used to pass input data to a method.

7: You can't move the transform class, you can only move the specific object.

8: It should be changed to "_playerTransform" instead of "Transform".

### Activity 3

[MG1 Breakdown Google Doc](https://docs.google.com/document/d/1xLpjOiC1mLK6nAbB_YaibtbYXvQONX3D-RQwwT5zzg4/edit?usp=sharing)

#

# W2

### Activity 1

![IMG_7378](https://github.com/user-attachments/assets/45b1be23-8abc-44aa-911b-d1233a43eb3d)

### Actvity 2

[MG2 Progress](https://github.com/UCI-GDIM32-W25/mg2-lilliaes-10/commit/d7f7decc0a58845372c4c37d598746e868b9487c)

In today's class I worked on MG2 by adding the background, ground, player, and coin sprites. I also set up the coin prefab and coded the player to jump on the space key and also not double jump.

#

# W3

### Activity 1 + 2

Weida + Leandro

### Activity 3

![IMG_7726](https://github.com/user-attachments/assets/88ea83aa-2e47-44d1-8526-c4d8b5b63e21)

#

# W4

### Activity 0

Weida & Leandro

### Activity 1

The locator objects are present logically, but not visibally in the game. This is because they are editor helpers and not a visual component.

### Activity 2

![Mg4 breakdown](https://github.com/user-attachments/assets/71d99b30-4834-4662-b3c9-cf8ac3677947)

### Activity 3

[MG4 Initial Commit](https://github.com/lilliaes-10/HW4/commit/e7af8ff7c60aaf4345560721bb39c7af1caa8283)
In class, I set up the background, vertical camera, ground, and player. I learned to download and upload and splice sprite sheets.

#

# W5

### Activity 1

I think using abstract Item class with the IBreakable interface makes sense for a game with different kinds of usable items. The Item abstract class works as a shared base that makes all items implement the Use() method, keeping code organized for handling different items in an inventory. The IBreakable interface is helpful for separating durability behavior from item behavior. If I were building a project, I would keep the design the same but maybe move durability logic into a shared class to avoid repeating similar code in each breakable item.

### Activity 2

The model in the W5demo2 are the scriptable objects EnemyStats and ItemW5Demo2, which are used in the enemy and player script to show the internal stat of the enemy and also the items in the player's inventory. The controller in the demo is the Player script, which detects input and moves the player based on the input received. The view is the dialogue UI and inventory UI.

### Activity 3

Scenario 1: Model View Controller with C# events

Scenario 2: Scriptable objects for weapons and abilities, inheritance for weapon abstract class, model view controller with C# events for the gunshots coming in contact with enemy. Finite state machine for animations and movements.

Scenario 3: Scriptable objects for the plants and rocks. Model view controller for the player to receive input and react to the movement input. Model for the data of the game.

### Activity 4

Attendance: Leandro, Lillian

[Final Project Proposal Google Doc](https://docs.google.com/document/d/1xISKeTxHcyg1ukxzz-i_5d-Cz9bvp_8rIGGyn6IEIXQ/edit?usp=sharing)

#

# W6

### Activity 1

Common student project performance issues include allocating strings frequently, too many debug messages, and putting things in Update() that doesn't need to run every frame.

Using Gizmos will be useful for my final project as that can be a good method to help debug positioning, velocities, and directions of the player and game objects. It will be significant in understanding how certain objects, the environment, and NPC's interact with the player, especially when attempting to solve issues in the code. Gizmos will help us to visualize with lines coming out of the objects to clarify details that may be easier to debug in through seeing it in the inspector rather than simply through analyzing lines of code. Especially for the final project, I will keep Gizmos in mind as it will be useful for debugging issues my team and I may run in to.

### Activity 2

Group Attendance: Lillian, Leandro

[Final Project Proposal Google Doc](https://docs.google.com/document/d/1xISKeTxHcyg1ukxzz-i_5d-Cz9bvp_8rIGGyn6IEIXQ/edit?usp=sharing)

#

# W7

### Activity 1

Raycasts have an origin point that go in a certain direction for a specific distance. They check what they hit first. In this game, the chicken has a spherical raycast so that it detects if there is anything in front of it, not just anything that may hit a single ray coming out of it. The direction is a vector that stops at the first collider it hits. NPCs should have a finite state machine that ensures it can only be in one state at a time, can't be running and idle or attacking and jumping.

### Activity 2

Attendance: Lillian, Weida, Leandro

### Activity 3

![IMG_8207](https://github.com/user-attachments/assets/d676ca87-987d-4ab1-bd04-c4e8c2afd6b6)

### Activity 4

[GDIM 32 Group Final Project Tasks Document](https://docs.google.com/document/d/1hls1AYtu9bNMllUslOCO5rB60zfJzVcmPYjtyw58uko/edit?usp=sharing)

### Activity 5

[Final Repository Commit Update](https://github.com/Weida758/GDIM32-Final/commit/99ffa49d6085c2aa6092867b9d46f25b0e2e5bc4)

In today's class, I worked on searching online for free character and resource assets for my group's game project. I was able to find an adventurer characters pack and basic collectible items/resources set to download and upload to our project.

#

# W8

### Activity 1

Shaders can be used to enhance visuals of object materials and scenic items in the Unity game. Animations from other sources might not work with other 3D models, as they have to be rigged to the specific model types. Additionally, you can add these effects in the scene through post provessing paclaging in the Unity registry. A new layer needs to be made to add the new volume component to it.

### Activity 2

Attendance: Lillian, Weida, Leandro

### Activity 3

Today I am going to work on finding more UI assets for the stamina, health bar, and small icons for stats screen (heart, sword, shield).

### Activity 4

[Final Repository Commit Update](https://github.com/Weida758/GDIM32-Final/commit/8613f650a8243c985a638f41aa29d9e3cacfea57)

In today's class I ended up finding audio assets for the UI, the walking sounds, hitting sounds, and background music for normal state and when fighting enemy state. I also found UI elements for the player stats including heart, sword, and shield elements.

















