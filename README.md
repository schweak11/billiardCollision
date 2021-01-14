# billiardCollision
Trajectory simulation of n elastically colliding billiard balls

The program calculates the trajectories of n particles in 3D in a box of specified dimensions. The particles move on a straight line except if they get too close. In that case, they perform an elastic collision that changes both trajectories.

The code is parallelized so several boxes with n particles are simulated with random initial conditions. For each thread, you can output all trajectories. You can also output a histogram of all velocities, to which all threads contribute.

Caveats: If the particles are initialized too close to each other, they perform a "continuous collision" that is physically wrong.
