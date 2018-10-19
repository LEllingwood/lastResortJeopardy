pick six categories of questions.  {television (67) , american history(780), hodgepodge (227), word origins (223), musical instruments(184), mythology(680)}

Create two grids: Grid 1 will list the categories.  Grid 1 will consist of one row with six cells. Now I want to just append the tvQuestion title so that the game is more flexible in terms of future updates (rather than hardcoding it.)  (create text node to attach to cells?)

Grid 2 will consist of five rows, six cells long.  Use Grid from previous assessment; extend class.  I want to orient the grid so that the cells are attaching to columns, rather than rows.  How the F do you do that?  (Will need a grid class and a cell class)

    Upon click of a cell, I want the clue to show up below the gameboard (since the question might be too large to fit in the cell).  I want the answer to also appear underneath the gameboard or if it should appear it the cell.  Cell should definitely have the value of the question.  create divs on the dom to which the question will be attached.

on page load - fetch each category. Fetch as part of a function in the creation of the grid(s)?

ensure grid provides dataset information when user clicks on a square. 

Ensure that questions increase in difficulty by using the "Value" key. How??

click on cell generates a new random question within the appropriate value range.

write code to move on to a new question when the value of the qustion is null.

add a button to make a guess, an input box at the bottom, and a clear game button that reloads page.
(Maybe use something on this page to load a new game?  https://stackoverflow.com/questions/3682805/javascript-load-a-page-on-button-click)
input box: https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_text_value2