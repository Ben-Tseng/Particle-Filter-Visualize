Particle Filter — Step-by-Step Breakdown An interactive visual guide explaining how to build up a particle filter for robot localization. 

What's Inside The page walks through the particle filter in six steps:
1.Overview — What the three questions are trying to achieve together. 
2.Initialization — Particles are scattered randomly across the map.
3.Predict(Q4)  — Every particle executes move() using the bicycle motion model.  
4.Update (Q5) — sense() computes bearing angles; particles closer to the true position get higher weights. 
5.Resample — High-weight particles are kept, low-weight ones are dropped. 
Loop (Q6) — Steps 3–5 repeat until particles converge on the robot's real position.

How to Use Open particle_filter_explained.html directly in a browser — no build step or dependencies required.
