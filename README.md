# Final-Unit-Project

## 1. Brief Description

A maze game where a ball moves by gravity through a maze that is filled with walls, traps, and a goal marking the end. Gravity will change the way the ball falls to guide it to the exit.



## 2. Things Being Modeled

A ball object that is affected by gravity and collisions.



A maze that uses walls, traps (traps like pendulums), and a goal area.



Walls that act as a barrier which the ball cannot pass through.



A goal that marks the win.



Holes/traps that reset the ball to the start.



## 3. Other Variables and Data Structures

A layout to represent the maze structure.



A list or array of wall objects that will be around the maze.



A list of hole/trap objects.



Gravity direction values (horizontal and vertical components).



The current level state (playing, won, lost).



Start and goal spots.



## 4. Setup Tasks

The dimensions of the maze.



Create all walls, traps, and the goal, as well as making sure they are in the correct spot.



Place the ball at the start.



Set down as the initial direction for gravity.



Initialize variables for tracking level progress or player status.



## 5. Flow of Draw

Continuously update the ball’s position based on gravity.



Detect collisions between the ball and walls, holes, or the goal.



If the ball hits a wall, stop or bounce its movement.



If the ball reaches the goal, display a win message.



If the ball falls into a trap, reset its position or display a fail state.



Redraw the entire maze and the ball every frame.



Read and apply player input to change the gravity direction.



## 6. Classes and Their Properties/Actions

Ball Properties: position, velocity, acceleration, radius, color.



Actions: update position, apply gravity, and detect and respond to collisions.



Maze Properties: a list of walls, traps, and the goal.



Actions: draw the maze and check for the win/loss conditions.



Wall Properties: location, width, and height.



Actions: detect collision with the ball.



Trap/Hole Properties: location, size.



Actions: detect overlap with ball, trigger loss/reset.



## Goal

Properties: location, size.

Actions: detect if there is an overlap with the ball and trigger the win.
