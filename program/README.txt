Authors : Cobi Nguyen
	  Zackery Wiegand

This README explains code snippets programmed in Scratch
    This README will also serve as our 'code' subfolder, we will add links and descriptions
to the README as me progress through the project. We will give a code subfolder with
the Scratch projects, if you want to download them and open them through a Scratch
desktop app, but using the URL's would probably be easier.

!!! INSTRUCTIONS TO RUN CODE !!!

    Scratch code can only be viewed on the Scratch website (https://scratch.mit.edu/)
or a Scratch desktop app. So in this Readme we will give you links to each project. 
Copy and paste the links in your browser URL if you don't wish
to run .bat files, or have a system other than Windows.

    You could also download and run our runCodeSnippets.bat that will open the 
code snippets in separate tabs in your default web browser. Once you are looking
at the program from scratch.mit.edu, you can run it or look at the code by clicking
the "See inside" button in the upper right of the window.
This .bat and instructions serve as our Makefile.

!!! FUNCTIONS !!!
Project Program
==============================================================
=== Snake Game ===============================================
==============================================================

URL : https://scratch.mit.edu/projects/386853145/

This is our projects big program. We are attempting to make a 
game of snake in scratch. 


To use the game just click the flag and the ball, which is the "snake",
will begin to move. Control the snake with your arrow keys and "eat" 
the fruit. When you collide with the apple you will gain a point, and 
the fruit will move somewhere else in the map. Do not run into walls
because that will cause the game to end, the snake will stop moving.


As of 4/20/2020 we have finished :
- Snake controls
- Fruit behavior (collision, repositioning, and point accumulation)
- Death by Walls (death when snake collides with wall).

We still wish to implement:
- A simple start menu
- Actually turn the snake into a snake.
	Right now the "snake" is just a ball, and does not grow as it eats.
	The trickiest part for the game will be to extend the snake, and have
	its extended segments properly follow the leader.
	We will also need to implment death by running into another segment.
- Simple gameover message displaying score and option to restart game.