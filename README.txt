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


To use the game just click the flag and you whould be presented with the Start Menu.

Clicking the start button will take you to the game.

Press any arrow key and the snake will begin to move.

As you eat fruit the snake will grow and your score will go up.
Watch out! As your score increases, so does the number of bombs 
on the map.

The game ends from you hitting the walls or a bomb.

Known Features??
We have all the bombs respawn at random locations everytime you get a point.
This makes the game more interesting, but there is a chance that a bomb will spawn
on top of the snake. You can crawl over yourself unlik normal snake games, so a 
strategy to try is consolidate your snake into a smaller area as it gets bigger.

Milestone 4
==============================================================
=== Add Sub Calculator =======================================
==============================================================

URL : https://scratch.mit.edu/projects/386806130/

This program is the more complex program for milestone 4.

This program is simple add or subtract calculator but the user
input is more complex than the Numbers program from milestone 3.

To use this program you :
 - click a number to set variable 'x'
 - click a number to set variable 'y'
   (you can continue to click numbers, the program will assign
   that number to x or y, alternating, starting on x.)
 - click the plus or minus (this sets the operation to add or subtract)
 - click the equal-sign to display your result

The variables are not erased after clicking the equal sign, so try adding
get a result, then click the minus, and get that result too without having
to reenter the x an y values.
==============================================================
=== Broadcast Example ========================================
==============================================================

URL : https://scratch.mit.edu/projects/386804360/

This small program shows how using broadcasts as subroutines,
allows the developer to call blocks of code across multiple sprites.

This program shows three different sprites taking turns talking, but
broadcasts could be use to have one sprite broadcast a message and two
other sprites act simultaneously on that message.

To use the program just click on the flag like always.

==============================================================
=== Block Example ============================================
==============================================================

URL : https://scratch.mit.edu/projects/386801587/

This small program shows the most basic use of a custom code block.
The developer can put their own code under a custom code
 block defnition, and then call that block elsewhere within
 the local sprite. This is exactly like function in any other
 popular language.
 
Use is as simple as clicking the green flag once you've opened
the program.

Milestone 3
==============================================================
=== Sort List ================================================
==============================================================

URL : https://scratch.mit.edu/projects/384847425/

This is the longer creative project of Milestone 3

Focuses on use of strings and string comparison.

To use the program build a list by clicking on the words, the list length
has no limit. You can then sort the list by word length by clicking the Up
or Down arrow which associate with ascending and descending order.

==============================================================
=== Numbers ==================================================
==============================================================

URL : https://scratch.mit.edu/projects/384783458/

This program features different operations you can do on numbers.
These are simple operations but all the basics are covered in this program.

The program starts with the variable being set to 0.
You can click on each of the operator buttons to modify the number.
+ and - modify the number by  + 1 or - 1.
* and / modify the number by * 2 or / 2.

Play around by clicking all the different operator buttons created.

==============================================================
=== Strings ==================================================
==============================================================

URL : https://scratch.mit.edu/projects/384792562/

This program features strings and booleans in use.

To use the program click on the picture, every two clicks and the cat 
will say the combination of those words.

Click the apple twice, cat says "AppleApple"

Click Pen then Pineapple, cat says "PenPineapple"

The cat only talks every two clicks, so if you click the apple once, 
nothing will happen. This feature is implmented by the use of booleans.

Milestone 2
==============================================================
=== 99 Bottles ===============================================
==============================================================

URL : https://scratch.mit.edu/projects/382779665/

This is our longer creative project for Milestone 2.

To run the program start it by clicking the flag, (this is the last time
I'll tell you to click the flag, all programs start with the flag).
Once the program starts there will be 99 bottles of sprite on 3 walls,
click a bottle, the bottle will sing a line to 99 bottles and then disappear.
As you continue to remove bottles by clicking on them, they will say how many
bottles of Sprite are on the wall.

This program really shows the power of the cloning feature provided by Scratch.
There are also many uses of If statements to control on the Sprites are positioned 
on the screen.

==============================================================
=== If Else Button Lock ======================================
==============================================================

URL : https://scratch.mit.edu/projects/382726883/

This functions has two sprites with separate code, button A and button B.
The two sprites share a variable, that prohibits button B from being 'On' 
unless button A is 'On' as well. 

To  use the program click the flag, and then try clicking the two buttons in different
orders, see when button B says it is 'On', and when it will repeatedly say it is 'Off'.

Displays use of If and If Else statements.

==============================================================
=== Loopz ====================================================
==============================================================

URL : https://scratch.mit.edu/projects/382730694/

This function displays use of repeat until loop, using a variable
i to keep track of the count. Every 10 iterations the i is reset
and begins counting from 0 again.

To run just click the flag and it does its thing, no user interaction
after beginning the program.

==============================================================
=== Forever Cloning ==========================================
==============================================================

URL : https://scratch.mit.edu/projects/382732347/

This program creates a clone of the original cat sprite, the clone
counts down from 5 and is then deleted. This will repeat forever until
the user clicks the big green button, which will delete the current clone and
hault anymore from being created.

This program uses the repeats blocks, forever block, and gives a simple example of
using the cloning functions provided by Scratch.


Milestone 1
==============================================================
=== Hello World ==============================================
==============================================================

URL : https://scratch.mit.edu/projects/379337442/

Note the comments mention how we wrote it for this Milestone, proof we aren't 
 just giving a link to somebody elses code.

This Hello World function is as easy as it gets, with two blocks.
 With start the function with "when (flag) clicked", and then cause the
cat sprite to say "Hello World!".

We have learned Scratch is really optimized for graphic response, and not so much
 a console with text output that we see in other languages. The point of a Hello World
function is to familiarize yourself with getting something to respond, and having the 
 cat say Hello World is how we approached it.

===============================================================
=== Right-Left ================================================
===============================================================

URL : https://scratch.mit.edu/projects/379338240/

This function Right-Left displays a few different blocks given for us to use.
 When reading the code you can see how Scratch approaches basic iteration, keyboard input,
and sprite movement. 

Even with a function as small as this we begin to see how intuitive the vernacular used to
 label the blocks is. It is kinda strange going backwards, coming from a couple years of coding
experience to a language designed to be a first experience.

The cat says what you should do to use the function, he will walk Right, 
 and then when prompted walk back Left. The function is done after this.

================================================================
================================================================
