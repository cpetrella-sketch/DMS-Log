My final project was inspired by the "Pattern Mutation" by Loren Schimdt.

My initial goal was to recreate the grid used, as well as making the random changes spread out from whichever square was being edited.

I started with a 2 by 2 grid, making sure that I had the tiles changing color properly. That was followed by making the tiles fit into the canvas, scaling to fit as needed.

Once I had made a square of tiles, I had to make a grid of grids. This was done easily enough, but pretty much just made a single grid with more tiles. The next step was copying the changes of one square to the others, which took awhile to make it stop trying to change squares that didn't exist.

The random changes were actually pretty easy, just changing the location data I was using to copy the changes by one each time it copied, combined with a random number generator to make it only occur some of the time.

The hard part was making the changes spread not from the left, but outward from the square altered. This was done with lessons learned from another class taken this semester. _Hi Professor Abdul-quader!_ I used the "queue" structure learned in data structures. I had to find someone else's code for that, since p5js didn't have a version itself. This is credited in the code.

As a last addition, I added a function to save a picture of whatever work was made by pressing "p" on the keyboard.

![pixlArt (4).png]({{site.baseurl}}/pixlArt (4).png)

It saves like that.

Possible methods of improving the code would be adding additional colors, or the ability to adjust how many large squares and/or how many tiles per square are on the canvas without directly editing the code.