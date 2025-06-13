# A-New-Spider-Game-solution

Download Here: [A New Spider Game solution](https://jarviscodinghub.com/assignment/a-new-spider-game-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

In this assignment you will be implementing a game that simulates a spider hunting for food.
This game is inspired by many earlier games, su h as the snake game available for mobile
phones and many other platforms (video available at https://www.youtube. om/wat h?v=z_
Ct-lKwSgo).
The game is played on a varying size grid board. The player ontrols a spider. The spider,
being a fast reature, moves in the pattern that emulates a Knight from the game of Chess
when it moves forward. On the other hand, sin e it is not equipped with eyes to see behind,
it emulates a King from the game of Chess when it moves ba kward. There is also an ant that
slowly moves a ross the board, taking steps of one square in one of the eight dire tions. The
spider’s goal is to eat the ant by entering the square it urrently o upies, at whi h point another
ant begins moving a ross the board from a random starting lo ation. The spider knows the
lo ation of the ant.
Game Denition
Figure 1: The illustration of the New Spider game
The above gure illustrates the game. The blue box shows the lo ation of the spider. The
green box is the urrent lo ation of the ant. The red boxes are the possible moves the spider
ould make. The yellow arrow shows the dire tion that the ant is moving – whi h, in this ase,
is the horizontal X-dire tion. When the ant is eaten, a new ant is randomly pla ed on one of
the borders of the board and assigned a random dire tion to move a ross the s reen, depending
on where it starts.
To simplify the game, assume that the ant only takes a single step forward ea h time the
spider moves. All your sear h algorithms should predi t the motion of the ant along with the
2
spider, be ause the position to whi h it will move next is deterministi . If the ant makes a move
that would take it o the board, the spider has failed to at h it, and a new ant is spawned as
if it had been aught.
Similar to the snake game, the game only ends if the spider makes a move that auses it
to step o the board.
Assignment Ob je tives
 Implement the New Spider game.
 Implement a Breadth_First Sear h for the spider to play the game.
 Implement Depth_First Sear h for the spider to play the game.
 Implement A* sear h.
 Implement two (2) dierent heuristi s for the spider to play the game.
 Implement a third heuristi whi h takes the average of the rst two heuristi s.
 Write a short report (no more than two (2) pages) about the state spa e of the game, and
about the hoi e of your heuristi s.
Questions
During the demo you should be prepared to dis uss the following questions:
 Whi h sear h worked best?
 Whi h heuristi s did you use?
 Why did you hoose these heuristi s?
 Does the ombination of the two heuristi s work better or worse than they do individually?
 How well do the sear hes work if you in rease the size of the board to 30×30 or 50×50.
 Whi h of the sear hes works best if you in rease the speed of the ant to two steps per
turn? Three steps?
Bonus
The following items are onsidered as bonus. You should work on these if you have ompleted
the required ob je tives.
 Instead of a new ant appearing every time the old ant is eaten, they appear at a onstant
rate, allowing multiple ants to appear at the same time.
 Two, three, or even more spiders simultaneously ompete for the same ant or the same
set of ants.
3
Tips
Don’t spend too mu h time on the graphi s. The sear h maybe slow. In this ase, think about
how you an optimize it. Command-line graphi s are perfe tly ne.
Your rst priority should be to make sure that the sear h works.

