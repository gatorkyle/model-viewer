# model-viewer
Interactive robotic arm model viewer, with matrix transformations implemented to support part connectivity.

Please view the included .mp4 for further demonstration.


Controls:

Select parts of the model using different key presses
  - B: Base
  - T: Icosahedron top
  - 1: First arm from the top
  - 2: Second arm, after the joint
  - P: Pen at end of second arm, with attached button
  - C: Camera, selected by default

After making a selection, an appropriate transformation can then be implemented using the arrow keys
  - Base: The arrow keys will move the entire model along the xz-plane.
  - Top: The left/right arrow keys will rotate the top along with the attached arm.
  - 1: The up/down arrow keys will rotate the first arm, with the pivot attached to top.
  - 2: The up/down arrow keys will rotate the second arm, with the pivot attached to arm 1.
  - P: The left/right arrow keys will rotate the pen along its latitudinal axis, with up/down along its longitudinal axis. Holding SHIFT and pressing the left/right arrow keys will twist the pen along its local y axis.
  - C: The arrow keys will rotate the camera around a sphere of radius 10, always pointed towards the center of the scene. Up/down shift by longitude, left/right shift by latitude.
