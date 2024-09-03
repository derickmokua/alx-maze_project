alx-maze_project

This project serves as the alternative 'Maze project' for the 'Research & Project Approval (Part 1)' within the ALX Software Engineering program.

 Maze Project Overview

Background Context  
The primary objective of this project is to create a 3D game using raycasting, simulating a maze-like environment.

Tasks

1. Walls  
   In this initial phase, you will need to:
   - Set up a window using SDL2.
   - Utilize raycasting techniques to render walls within the window.
   - Camera rotation during execution is not required at this stage; however, you must include a method in the code to adjust the camera's angle for testing after recompilation.
   - Ensure the wall colors differ from those of the ground and ceiling.
   - A file-based map is not mandatory at this stage, but you must offer a means to modify the map directly within the code (e.g., using an array of integers or characters).

2. Orientation  
   - Walls should be colored differently based on their orientation:
     - At minimum, distinguish between walls facing NORTH/SOUTH and those facing EAST/WEST with unique colors.

3. Rotation  
   - Implement functionality to rotate the camera during execution:
     - For example, allow rotation with the left and right arrow keys, or mimic an FPS game with mouse movements.

4. Movement  
   - Enable camera movement during execution:
     - For instance, use the 'W', 'A', 'S', 'D' keys for directional movement.

5. Collision Detection  
   - Integrate collision mechanics, treating the camera as a player:
     - The player should be prevented from passing through walls.
     - Allow the player to slide along walls rather than stopping abruptly upon collision.

6. Parser  
   - Develop a parser to load the map configuration from a file:
     - Define your map standards (e.g., specific characters for walls and empty spaces, file extension types, etc.).
     - The program should accept the path to the map file as a parameter upon execution.

7. Map Rendering  
   - Render the map within the game window:
     - You have creative freedom regarding the map’s positioning and colors.
     - Include an option to enable or disable the map display during gameplay.
     - Display the player's line of sight on the map.

8. Coding Style and Documentation  
   - Ensure your code adheres to the Holberton School coding standards.
   - Properly document your code following the Holberton School guidelines.
   - You can validate this by following the instructions provided in the designated repository.
   - Remember that the review will cover all files in your submission directory, so keep it clean and organized.

9. Textures  
   - Introduce textures to your walls to enhance the visual appeal.

10. Multi-Tasking  
    - Implement functionality to handle simultaneous actions, such as moving and rotating concurrently:
      - For instance, if 'W' and 'D' are pressed, the player should move forward and to the right simultaneously.
      - Avoid conflicting actions, such as moving forward ('W') and backward ('S') at the same time.

11. Ground and Ceiling Textures  
    - Apply textures to the ground and ceiling to improve visual depth and realism.

12. Weapons  
    - Add weapon textures to introduce a combat element to the game.

13. Enemies  
    - Integrate enemies within the game to challenge the player.

14. Weather Effects  
    - Introduce weather effects, such as rain, with the ability to toggle it on and off via a key press.

15. Extra Features  
    - Explore additional creative enhancements such as shadows, special lighting effects, or any other innovative elements to elevate the game experience.


