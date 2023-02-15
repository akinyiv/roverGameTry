# roverGame-Pseudocode

Initialize variables `x`, `y`, `direction` with the initial position and direction of the rover.
Initialize a variable `commands` with the input command string.
Loop through each command in `commands`:
   If the command is "L", turn the rover 90 degrees left.
   If the command is "R", turn the rover 90 degrees right.
   If the command is "F", move the rover forward one step in the current direction.
   If the command is "B", move the rover backward one step in the current direction.
End loop.
Print the final position of the rover, `x`, `y` and `direction`.
