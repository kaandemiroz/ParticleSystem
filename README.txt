CSCI 520, Assignment 2

Osman Kaan Demiroz

================

3D Particle System

- Hold right click to rotate camera, similar to HW1; press Z/X to zoom, R to reset camera position, P to pause. In addition, press B to toggle showing the bounding box, and G to toggle showing the Grid.
- Left click to add an attractor in 3D space. Particles will always move towards the closest attractor.
- Middle click to add a repeller in 3D space. Repellers will push away particles that are within a certain distance. (A trick I used in the video is to add an attractor and repeller on the same point, which creates a sphere of particles around the point)
- You can add up to 50 attractors and 50 repellers.
- Attractors can be seen as tiny green dots, while repellers are tiny red dots. Press D to toggle displaying these dots (not in video).
- Press Backspace to remove the last added attractor. Repeatable.
- Press Delete to remove the last added repeller. Repeatable.
- Particles have a lifetime, and new particles spawn when old particles expire. (Actually recycled)
- When there are no attractors, particles spawn randomly within the bounding box. As long as there is at least 1 attractor, particles will spawn around the closest attractor, and move towards its center.