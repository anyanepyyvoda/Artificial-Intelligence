River Crossing Problem - A* Search

This project was developed as part of the Artificial Intelligence course in my Computer Science degree. The goal was to solve a classic pathfinding problem using A* search with a closed set.

## Problem Description

The program addresses a variation of the River Crossing problem, where a group of family members needs to cross a river in the least amount of time, using a single lantern that limits the total time allowed for all crossings.

The user provides:
- The number of family members
- The individual crossing time for each person (must be unique)
- The maximum time the lantern can last

The program then finds the optimal crossing strategy using the A* search algorithm and prints the solution step-by-step.


## Execution

 1. Open the command prompt.
 2. Go through the command prompt and navigate to the folder containing the source code files (State.java, SpaceSearcher.java and Main.java):
 >> cd path
 3. Compile the program:
 >> javac State.java SpaceSearcher.java Main.java
 4. Run the program:
 >> java Main

## Example Input
Please enter number of family members: 5
Enter the crossing time for member 1: 1
Enter the crossing time for member 2: 3
Enter the crossing time for member 3: 6
Enter the crossing time for member 4: 8
Enter the crossing time for member 5: 12
Enter the lantern time: 30
