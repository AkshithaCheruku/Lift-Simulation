This project simulates an elevator control system with specific rules for its operation.

Features:
Elevator Simulation: Simulates elevator movement between Ground level, Level 1, and Level 2.
Level Controls: Provides up and down buttons on each level.
Conditional Movement: Enforces rules for elevator movement based on button presses and current level.
Usage:
Interface: The home page displays the elevator and control buttons for each level.
Calling the Elevator: Ground level has only the UP button enabled. Level 1 has both UP and DOWN buttons enabled. Level 2 has only the DOWN button enabled.
Elevator Movement:
From Ground Level:
Clicking UP moves to Level 1 (5 seconds).
Stops at Level 1 only if UP is pressed on Level 1, otherwise goes to Level 2.
From Level 2:
Clicking DOWN moves to Level 1 (5 seconds) or Ground Level (10 seconds).
Stops at Level 1 only if DOWN is pressed on Level 1.

