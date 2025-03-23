# A-and-IDA-searching-algorithm
This project is a fun and interactive simulation where an AI agent navigates a grid using the A* search algorithm to complete tasks while avoiding obstacles. It’s built using Python and Pygame, making it visually engaging.

agent.py (The Brain of the Agent)
This file defines the agent, which moves around the grid looking for tasks. It uses the A* algorithm to find the shortest path to its goal, making smart decisions about where to go next. It also keeps track of completed tasks and how much effort (cost) it takes to reach them.

environment.py (The World Setup)
This file creates the grid-based world where the agent operates. It randomly places tasks for the agent to complete and barriers that act as obstacles. It also ensures that tasks are placed in reachable locations.

run.py (The Visual & Control Panel)
This is where everything comes to life! It sets up a Pygame window, displays the grid, and animates the agent’s movements. You can start the simulation by clicking a button, and the agent will begin its journey, moving efficiently to complete tasks while navigating around obstacles.
