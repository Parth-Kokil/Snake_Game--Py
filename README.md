# 🐍 Snake Game (Python Turtle Graphics)

This is a classic Snake Game built using Python and the Turtle graphics module. It demonstrates object-oriented programming (OOP) concepts and event-driven programming with real-time user input.

 🎮 Features

* Snake controlled by arrow keys (`Up`, `Down`, `Left`, `Right`)
* Scoreboard to keep track of points
* Food appears randomly on the screen
* A snake grows longer when it eats food
* Collision detection:

  * Wall collision ends the game
  * Tail collision ends the game
* Smooth animation using `screen.tracer(0)` and `screen.update()`

 🛠️ Technologies Used

* Python 3
* Turtle module (standard graphics library in Python)

 🧱 Project Structure

.
├── main.py         # Main game loop and screen setup
├── snake.py        # Snake class: movement, growth, collision logic
├── food.py         # Food class: random food positioning
├── scoreboard.py   # Scoreboard class: score tracking and game over display
 
 🚀 How to Run

1. Make sure Python 3 is installed.
2. Clone the repository or download the source code.
3. Run the `main.py` file:


python main.py


 ✅ Learning Objectives

* Implement game logic using object-oriented programming
* Work with the `turtle` module for graphics
* Handle user input using keyboard events
* Use collision detection to control game flow
