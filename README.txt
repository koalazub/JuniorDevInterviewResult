Junior dev position

This project was for a junior development position at an interactive marketing firm. The prereqs for completion were the following:

Within Unity:

Create an endless runner mode
Create a functioning leaderboard that displays a score
Create an obstacle
Indicate somehow that the player has hit the object
Ensure that there is a penalty mechanic for hitting the obstacle
The score was based on the time you've been playing and was to be saved to the leaderboard. In this version I did away with the leaderboard and chose to focus more on object referencing and balancing the managers.

The mechanics in this game was more or less the crux of the project. I implemented a mouse click event that registers whether you've performed a swipe by holding the left mouse button down, moving the mouse along a quadrant(if we visualised a cartesian graph, say along the 2nd quadrant) and executes a function depending on the quadrant. In this case, it was a jump if you swipe along the y-axis in the 1st and 2nd quadrants.

I spent a little too much time toying with components due to issues with the addExplosiveForce rigidbody function and wasn't able to fully complete the project.
