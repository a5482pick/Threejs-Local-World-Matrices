__LocalAndWorldMatrix.html__ creates 4 generations of ancestry of objects... the largest cube is the 'grandparent', the 2nd largest is the parent and the 3rd is the child. &nbsp; The grandchild is the cuboid that automatically moves away along the x axis. &nbsp; The alerts in order are: grandchild.matrix.elements, grandchild.matrixWorld.elements and grandchild.modelViewMatrix. &nbsp;The exercise demonstrates when matrices do and do not need to be manually updated, and it also clearly demonstrates exactly what 'matrix' and 'matrixWorld' are. &nbsp; Also demonstrated is how to manually calculate the modelViewMatrix using the inverse of the camera's matrixWorld: this simple example has the camera initially on the x-axis, looking at the origin from x = 50... since 'grandchild' is also on the axis, we see that the positional component of the modelViewMatrix is simply 13.5 - 50 i.e. -36.5. &nbsp; NOTE: The 'camera' is given automatic motion, but one degree of freedom is provided so that some manual camera motion using the mouse is also possible.
