# CONNECT_FOUR_GAME
- First we will import all the necessary libraries.
- Next we will define the colours blue, black, red and yellow as global static variables. These values are going to be rgb values.
- We will initialize global variables called ROW_COUNT and COLUMN_COUNT. Number of rows are 6 and number of columns are 7.
- Then we create 5 functions named create_board( ), drop_piece( ), is_valid_location( ), get_next_open_row( ) and print_board( ).
- Then we create a function called winning_move() and we check for horizontal locations to win, vertical locations to win, positively and negatively sloped diagonals to win.
- In horizontal and vertical locations, we create a nested for loop for the rows and columns and check an if condition statement to see if the piece has been dropped to that location on the board. If the if condition is satisfied, it will return TRUE. We will repeat the same procedure for vertical locations, positively and negatively sloped diagonals as well.
- In the function def draw_board( ), pygame.draw is a module for drawing shapes.
- pygame.draw.rect is used to draw a rectangle. Now we will define the triangle. Define the height and width and the position.
- So the position is going to be, c*SQUARESIZE and the position of the y-axis is going to be r*SQUARESIZE+SQUARESIZE.
- Height and width are going to be the other two parameters and thats just going to be SQUARESIZE, SQUARESIZE. Repeat the same procedure for circles as well.

