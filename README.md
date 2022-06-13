# cub3d

| Specs  | Explanation |
| ------------- | ------------- |
| Program name | cub3d |
| Turn in files | All your files |
| Makefile | all, clean, fclean, re, bonus |
| Arguments | a map in format \*.cub |
| External functs. | - open, close, read, write, <br/> printf, malloc, free, perror, <br/> strerror, exit <br/> - All functions of the math library <br/> - All functions of the MinilibX | 
| Libft authorized | Yes |
| Description | You must create a "realistic" 3D graphical representation of the inside of a maze from a first-person perspective. You have to create this representation using the Ray-Casting principles mentioned earlier. |

The constrains are as follows:
- You must use the miniLibX. Either the version that is available on the operationg system, or from its sources. If you choose to work with the sources, you will need to apply the same rules for your libft as those written above in Common Instruction part.
- The management of your window must remain smooth: changing to another window, minimizing, etc.
- Display different wall textures (the choice is yours) that vary depending on which side the wall is facing (North, South, East, West).
- Your program must be able to set the flooer and ceiling colors to two different ones.
- The program displays the image in a window and respects the following rules:
  - The left and right arrow keys of the keyboard must allow you to look left and right in the maze.
  - The W, A, S, and D keys must allow you to move the point of view through the maze.
  - Pressing ESC must close the window and quit the program cleanly.
  - Clicking on the red cross on the window's frame must close the window and quit the program cleanly.
  - The use of images of the minilibX is strongly recommended.
- 
