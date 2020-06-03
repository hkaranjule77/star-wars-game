# project - star wars game
# author - Harshad Karanjule
# computer graphics project
# language - c language


INTRODUCTION :-
It is a game with theme based on first movie of STAR WARS.
This theme was suggested by my close friend Gaurav Garmode.

There are three ships kinds of ship -
1) X-Wings (player)
2) Tie-figher (enemy)
3) Darth Vader's Tie-fighter (enemy)

Like movie, Luke Skywalker's planet is invaded by Deathstar.
So he starts his journey towards it, fights with Tie-fighers and 
for destroying Deathstar.

Hence, game starts with the Luke Skywalker's ship(player) entering the
Screen which is invaded by Tie-fighter(enemy) in space. When player 
destroys all Tie-fighers, he/she is able to go close to the Death star's 
surface and there needs to face some other tie-fighers again
 with some other surprise entry of Darth Vader's ship with 
special endurance.
Finally, player has fire laser into the hole of Deathstar to destroy it.


TECHNICALITIES :-
It is powered by graphics.h, dos.h, stdlib.h libraries of c language. 
It uses bitmap array 
images to show various components of games like ship, numbers, icons, etc.
This images are blinked by calling user-defined functions coded with 
putpixel function of graphics.h library.
With help of sleep function of dos.h, to create proper time interval in 
frames.
Also, rand function make possible to generate randomness for single 
every time

CONTROLS :-
Controls are pretty simple like old mobile games.
So, controls for Luke Skywalker X-WING Spaceship are-
    2 - Moving ship in Upward direction
    8 - Moving ship in Downward direction
    5 - to Fire laser beams from ship
