# 2D Table Tennis Pro (Single-Player Pong)

A 2D single-player ping pong game developed inside a single file using pure JavaScript, CSS3, and the HTML5 Canvas API. Built as part of the technical task submission for the AWS Student Builder Group core selection.

## 🕹️ Live Demo
Play the game live here: [https://nairmeenakshy2007-ops.github.io/2d-ping-pong-game/]

## 🎮 Controls & Gameplay
- **Player Paddle:** Use `W` / `S` or `Up Arrow` / `Down Arrow` to move up and down.
- **Timer:** The game runs for **60 seconds**. A game-over screen automatically displays the winner when time runs out.
- **Scoring:** Awarded when the ball passes an opponent's goal line. The ball resets to the center and serves toward the player who just scored.

## 🛠️ Technical Highlights & Constraints Followed
- **Zero Physics Engines:** Manual AABB (Axis-Aligned Bounding Box) and Circle collision detection without external physics libraries.
- **Dynamic Trajectory Angle:** Bounce angles dynamically adjust based on where the ball strikes the paddle face (up to 60° max angle).
- **Web Audio API:** Synthesized contact sounds for paddle hits, table bounces, and point scores using pure JavaScript oscillators.
- **Simulated 3D Height Arc:** Ball vertical height ($z$-axis) and dynamic shadow projection on the table surface.
- **AI Tracking with Speed Threshold:** Automated opponent tracking with movement delay thresholds to prevent jitter and allow strategic player shots.
