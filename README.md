# savePrincess
This C# program solves the "Save Princess" problem, where the bot must rescue the princess trapped in a square grid. 

**************************************************************************************************************************

## Princess Rescue in a Grid

This C# solution rescues Princess Peach trapped in one of the four corners of a square grid while the bot is in the center. It calculates the shortest path to reach the princess and prints the sequence of moves required to rescue her.

### Solution Description:
- Defines a method `displayPathtoPrincess` that takes the size of the grid `n` and the grid itself as parameters.
- Locates the positions of the bot ('m') and the princess ('p') in the grid.
- Calculates the number of moves needed to reach the princess based on their positions.
- Outputs the sequence of moves ('UP', 'DOWN', 'LEFT', 'RIGHT') to the console to rescue the princess.

### Usage:
1. Implement the `displayPathtoPrincess` method in your C# project.
2. Pass the size of the grid and the grid itself to the method.
3. The method will calculate and print the sequence of moves to rescue Princess Peach.

### Notes:
- This solution assumes the input grid follows the specified format with the bot represented by 'm' and the princess by 'p'.
- Customize the method as needed to integrate it into your application logic.

