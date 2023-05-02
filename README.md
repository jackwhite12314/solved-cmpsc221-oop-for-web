Download Link: https://assignmentchef.com/product/solved-cmpsc221-oop-for-web
<br>









<h1>Background</h1>

According to Wikipedia Connect 4 is, “a two-player connection game in which the players first choose a color and then take turns dropping one colored disc from the top into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one’s own discs.”

<h1>Objectives</h1>

By completing this assignment, students should be able to:

<ul>

 <li>Write graphical programs using buttons and labels from JavaFX</li>

 <li>Explain how to build programs using JavaFX along with inheritance and/or interfaces</li>

</ul>

<h1>Assignment</h1>

This week, you will work to create a simple two player version of Connect 4.  Your game should be able to determine a winner or if the game results in a tie.  You must also have a button that will reset the game so it can be played again.

<strong>Statement.txt (5 points) </strong>

As with all assignments, please make sure to submit a completed statement.txt.

<h1>Design</h1>

<ol>

 <li>What are five classes from JavaFX you will need to complete this assignment? What do you expect to use each class for?</li>

 <li>We have to be able to track whether a spot is marked as Red, Black, or unmarked so we can figure out when someone wins or if there is a tie. How might we do this without having to do lots of string comparisons?</li>

 <li>Is there a way we could perhaps use inheritance or interfaces when designing our board spaces to make determining a winner easier? If so, explain it.  If not, explain why not.</li>

 <li>Write an English language algorithm for resetting the board. Be sure to explain what you have to do (and in what order) in order to reset the board.</li>

</ol>

<h1>Implementation</h1>

Write a program that will let two users sitting right next to each other play a game of Connect 4 that meets the following criterion:

<ul>

 <li>The game should be able to be reset so it can be played multiple times.</li>

 <li>The game ends when one person has won or there is a tie.</li>

 <li>The winner should be printed to the command line.</li>

 <li>The user should be able to select a column and have their token (red or black) occupy the lowest available space on the column. (Note: This doesn’t have to be be fancy, a button at the top of the row is fine.)</li>

</ul>

<h1>Style</h1>

As with all assignments, ten points of your grade are connected to how well you follow the style guidelines detailed on Canvas.

<h1>Notes</h1>

<ul>

 <li>A sample layout (minus the reset button) for tic-tac-toe can be found on page 806 of your book. You do not have to use their X and O images to get a good grade on this assignment.  Your reset button can be wherever you want it to be, but it must be visible to the user as to where this button is.</li>

 <li>Red should go first.</li>

 <li>Unlike past assignments, I am fine with the main class being the board, but the board class must be called java.</li>

 <li>Once a space is taken, you have to make sure that it cannot be claimed by the other player. For example, if Red picks a spot Black cannot come in and take it.</li>

</ul>


