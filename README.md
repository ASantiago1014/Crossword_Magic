This is my final project for my app development class. This project is a simple crossword puzzle game made using an Android App Development tool and the Java Programming Language.
I did not create this whole project by myself. My teacher provided my class with a lot of the code, giving us a “skeleton,” where we would have to fill in certain lines that he 
left blank. In the source file of the project, there are seven class files:

1)	CluesFragmentView.java: This class displays the clues for the user under the puzzle itself, allowing the user to scroll up and down to look at what they need, whether it be 
the puzzle box itself, or the numbers and clues for the puzzle. 

2)	CrosswordMagicViewModel.java: This class reads the list of clues and answers from the input file and uses the answers to generate blank white squares over a solid black 
base surface. The program generates the correct length of white squares to perfectly fit each answer for the puzzle based on if they are horizontal or vertical. 

3)	MainActivityView.java: This class is the main view class that establishes the view of the game. The view saves the instance of the current state if the user chooses to 
change to a different window, allowing the user to come back to the game where they left off when swapping back over. 

4)	MainFragmentView.java: This class extends the Fragment class and implements an onClickListener to create views and establish an onClick method.

5)	PuzzleFragmentView.java: This class establishes the main solid black base for the puzzle that the blank white squares lay on. This creates the general “black-white square” 
scheme that is a popular look for crossword puzzles. This class computes the square and font sizes, sets the container sizes, and populates the squares accordingly. 

6)	TabPagerAdapter.java: this is the class that initializes the fragment views that are used for the puzzle.

7)	Word.java: establishes the Word class to parse the answers for the puzzle and establishes methods that can be used with any Word objects. 
