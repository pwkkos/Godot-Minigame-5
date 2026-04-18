# Godot Minigame 5

## Devlog

How my cone count UI works is that when the player collides with a cone, the cone will detect the collision using the "\_on\_body\_shape\_entered" function and check whether or not the body is a vehicle (aka the player). Once it is confirmed that the body is a vechicle, the cone will increase the "cones\_hit" variable by calling the function, "\_increaseConesHit()" within the time UI script, increasing the number of cones hit by 1. After the number is updated, the conesText label will change to display the current number of cones hit through a string format. In short, each time the player hits a cone, the number of cones hit will be increased and displayed on the player's screen.

## Open-Source Assets

* [Car movement scripts \& car/racetrack models](https://github.com/DAShoe1/Godot-Easy-Vehicle-Physics/tree/main)
* [Racing props](https://atomicrealm.itch.io/modular-roads)
* [Finish line 3D model](https://sketchfab.com/3d-models/finish-line-7ec1d8194ddf46e6b398d336df0b5d7a)

