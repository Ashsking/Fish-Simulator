Fish Simulation in Java

This project is a fish simulation developed using Java. The simulation involves animated fish with different shapes and colors, moving in a randomly generated aquatic environment. 
Users can interact with the fish by clicking on them to change their direction.

 Features

- Interactive Mouse Clicks: Clicking on any fish changes its swimming direction.
- Custom Fish Shapes: The fish come in two different shapes: triangular and round.
- Color Variations: Only red, blue, and green fish are visible in the simulation.
- Speed Dynamics: Triangular-headed fish swim faster than round-headed ones.
- Random Movement: Fish move randomly, but you can influence their direction by clicking on them.

 Technical Details

- Random Shape and Speed Generation: Each fish is randomly assigned either a triangular or round shape and a speed corresponding to its shape.
- Dynamic Color Selection: Fish colors are limited to red, blue, and green for visual clarity and contrast.
- Mouse Interaction: A simple mouse event listener allows users to change the direction of any fish by clicking on it.
- Collision Detection: Fish will change direction when they hit the borders of the screen, ensuring continuous movement.

Setup and Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/Ashsking/Fish-Simulation.git
   ```
2. Open the project in your favorite IDE (e.g., Eclipse, IntelliJ).
3. Compile and run the `Fish.java` class to start the simulation.

Future Enhancements

- Additional fish shapes and colors.
- Enhanced collision detection.
- Customizable aquarium size.
- Fish AI for more realistic movements.

