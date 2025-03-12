# Spaceship Asteroids Game

Welcome to **Spaceship Asteroids**, a retro-futuristic arcade game where you navigate a spaceship through an asteroid field, avoiding collisions and shooting asteroids to survive and score points. This game is built entirely using HTML, CSS, and JavaScript, with no external libraries or frameworks.

## How to Play

- **Move the Spaceship**: Use the arrow keys (`↑`, `↓`, `←`, `→`) to navigate the spaceship.
- **Shoot Lasers**: Press the `Space` key to shoot lasers and destroy asteroids.
- **Hyperspace**: Press the `H` key to activate hyperspace and teleport the spaceship to a random location. Be careful—there's a small chance of teleporting into an asteroid!
- **Avoid Collisions**: Colliding with asteroids or their fragments will reduce your lives. You start with 3 lives.
- **Score Points**: Destroy asteroids to earn points. Larger asteroids give more points.

## Game Features

- **Retro-Futuristic Design**: Simple and clean visuals using pure HTML and CSS.
- **Starfield Background**: A dynamic starfield with parallax scrolling for depth.
- **Animated Spaceship**: The spaceship's propellant animates based on movement.
- **Asteroids**: Randomly generated with varying sizes, speeds, and rotation.
- **Laser Shooting**: Animated laser beams with a cooldown mechanic.
- **Hyperspace Feature**: Teleport the spaceship with a cooldown and a small risk of malfunction.
- **Scoring System**: Earn points for destroying asteroids, with higher points for larger asteroids.
- **Game Over Screen**: Displays your final score and allows you to restart the game.

## Code Structure

The game is written in a single HTML file (`index.html`) with the following structure:

- **HTML**: Defines the game elements (spaceship, asteroids, lasers, HUD, and game over screen).
- **CSS**: Handles the styling and animations for the game, including the starfield, spaceship, asteroids, and lasers.
- **JavaScript**: Manages the game logic, including:
  - Spaceship movement and controls.
  - Asteroid generation and movement.
  - Laser shooting and collision detection.
  - Scoring and lives system.
  - Hyperspace functionality.
  - Game over and restart logic.

## How to Run the Game

1. Clone the repository or download the `index.html` file.
2. Open the `index.html` file in your web browser.
3. Start playing!

## Bonus Challenge: Hyperspace Malfunction

The hyperspace feature adds an extra layer of risk and excitement. When activated, the spaceship teleports to a random location, but there's a small chance it could teleport into an asteroid, resulting in an instant collision. Use it wisely!

## Future Improvements

- Add sound effects for shooting, collisions, and hyperspace.
- Introduce power-ups (e.g., shields, rapid-fire lasers).
- Add levels with increasing difficulty and boss asteroids.
- Implement a high-score system using local storage.

## Credits

This game was created as a fun project to demonstrate the capabilities of HTML, CSS, and JavaScript for building interactive web games. Feel free to modify and expand upon it!

---

Enjoy the game and may the stars guide you to victory! 🚀
