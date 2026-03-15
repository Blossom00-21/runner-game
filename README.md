### **Endless Runner Game (Three.js)**

**Overview**

This project is a 3D Endless Runner Game developed using Three.js. The player controls a runner moving along a three-lane track, avoiding obstacles while collecting items to increase their score.

The project follows the theme “Cliché.” Endless runner games are one of the most common and recognizable game genres, often used as examples in beginner game development. This project intentionally embraces that concept by recreating a familiar and widely used game mechanic.

The game continues indefinitely until the player collides with an obstacle.

**Gameplay**

The player runs forward automatically while obstacles and collectible items appear on the track. The objective is to switch lanes to avoid obstacles and collect shakes to increase the score. The longer the player survives, the greater the distance covered.

**Controls**

Key| Action
← Arrow| Move left
→ Arrow| Move right
Shift| Run faster
Restart Button| Restart the game

**Features**

- 3D gameplay using Three.js
- Three-lane movement system
- Random obstacle spawning
- Collectible items (shakes)
- Distance and score tracking
- Game Over screen with restart option
- Infinite ground simulation

**Technology Stack**

- HTML5
- CSS3
- JavaScript (ES6)
- Three.js
- GLTFLoader


**Running the Game**

Run the project using a local server.

Example:

python -m http.server

Then open:

http://localhost:8000

You may also use VS Code Live Server.

Opening the HTML file directly may prevent ".glb" models from loading due to browser security restrictions.


**Purpose**

The goal of this project is to demonstrate basic 3D browser game development concepts, including rendering, object spawning, collision detection, and player input handling using Three.js.



**License**

This project is intended for educational purposes.
