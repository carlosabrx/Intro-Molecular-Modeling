# Intro-Molecular-Modeling

This is an introductory project into Molecular Statistics. It attempts to simulate physical systems and reinforcing object-oriented programming skills with Python on Jupyter notebooks. The main goal for this project is to initialize random positions with random velocities across a 2 dimensional vacuum space propagating over a line of time.

Starting with introducing variables, it is known n_particles is the amount of free particles in the box. Then, n_steps is the number of steps each respective particle will randomly take. Width is the length of the box. Finally, dt refers to the amount of time particles propagate over their random distances.

Lists for positions and velocities were created to save all values. These values were then introduced into a random_walk function to iterate over all values presented. After calculating all necessary variables, pyplot and py3Dmol were used to visualize and simulate noninteracting free particles in 2D vacuum space.

What is ultimately shown is how free particles move in a vacuum space when they can't feel each other and have intrinsic kinetic energy to their systems.
