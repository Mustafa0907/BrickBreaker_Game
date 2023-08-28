Task-1

The player will control the paddle. The paddle will be controlled by the player class which will be a singleton. The paddle's size can enlarge or reduce. Similarly, the paddle's speed can increase or decrease depending on the powerup.

At the start of the game, the ball will be sticking to the paddle and will be launched when space is pressed.

When a powerup is gained, the ball will stick to the paddle every time

The paddle will fire if a powerup is gained

The ball will bounce around the map. When a powerup is gained, the ball will produce 2 more balls which will bounce around.

If all the balls fall through the floor, the player looses a life, when all the lives are lost, the game ends

If all balls are lost, the player will lose a life and the ball will reset at the top of the player

=============================================================

Task-2

There will be different types of bricks.

Some bricks will break with a single hit

Some will break by 2 hits

Some will break by 3 hits

Some will not break (if only these bricks are left, the balls will automatically turn red indicating that they will break anything)

All of these bricks will have the moving variants which will move left and right if space allows

All of these bricks will be created by a BrickFactory

=============================================================

Task-3

Upon breaking a random brick, a powerup will be produced randomly

All powerups will be produced by a PowerupFactory

Powerups will:

Increase the size of paddle

Decrease the size of paddle

Increase the paddle speed

Decrease the paddle speed

Make every available ball to produce 2 more balls which will be launched in random directions

Make the ball turn red indicating that the ball is a fireball which destroysÂ all bricks

Gain a life

Help paddle fire with the SPACE key

All powerups will fall down and will need to be caught


=============================================================

Task-4

The current state of the game will be stored when the user presses the 'Escape' key

If the user chooses to start a saved game, then the game will restart from the saved state

There will be a start menu that will allow the player to start a new game, load a saved game or exit

When the game ends, the user should be able to restart the game or exit the game

The score, the Level number and the number of lives left (from a total of 3) will always be displayed on the top

=============================================================

Task-5

Create a class that generates a random level through code. The level should be playable and should not create a deadlock.

=============================================================