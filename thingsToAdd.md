Make a box jump over spikes and you win after you jump over all the spikes

logic: 
spikes move toward box, spacebar to jump, if you collide with the spike you lose

floor logic:
y = 400 fill

box on floor logic:
floor top = 400
box bottom = 400

moving spike logic:
x coords move in unison

respawning spike logic:
if v3 is off screen then draw on the right side
off screen = -50

jump logic:
check for keys pressed
if key pressed = what the user pressed then jump

collision logic:
if bottom left or bottom right of box collides with the left and top vertex of the triangle then game over

obstacle speed up logic:
add a rate after each triangle respawn

components:
player box
floor
jump button
spikes(triangles)
collision
restart 