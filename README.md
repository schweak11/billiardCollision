# billiardCollision
Trajectory simulation of n elastically colliding billiard balls

The program calculates the trajectories of n particles in 3D in a box of specified dimensions. The particles move on a straight line except if they get too close. In that case, they perform an elastic collision that changes both trajectories.

Caveats: If the particles are initialized too close to each other, they perform a "continuous collision" that is physically wrong.
