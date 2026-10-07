# PRACTICE 1: DOCUMENTATION OF LOCALIZED VACUUM CLEANER

 Irene Diez de Toro
 
 October 2026 - Robotic Software Engineering

# 0. INTRODUCTION

For the initial practical assignment of this course, we are required to implement a BSA (Backtracking Spiral Algorithm) for a vacuum-cleaning robot that uses self-localization. To accomplish this, we are provided with a pixel-based map representing the obstacles within a house, and the objective is to cover as much of the available area as possible in order to achieve an efficient and thorough cleaning of the entire surface. In addition, the corresponding theoretical background and guidelines for implementing the algorithm are provided.

# 1. THEORICAL CONCEPTS

To create the algorithm solution we needed the next theorical concepts:
- ***Conversion between different representations***: The conversion between different types of variables is essential in this practical assignment, as the algorithm is fundamentally based on it. It is necessary to understand the conversion between 3D and 2D, or, more specifically, the conversion of the robot’s real-world coordinates in Gazebo into specific pixels on the provided map, and vice versa. In this process, we must take into account the transformations applied to these points and use a common transformation that accurately calibrates these conversions. Additionally, it is necessary to establish a relationship or conversion between pixels and cells, since the map must also be divided into a grid of cells.
- ***Coverage and decomposition, and traveling between segments***: On the other hand, when developing the algorithm, we need to determine the different possible paths and decide which one to follow based on the specific requirements of the algorithm. In order to move the robot, the recommended approach is to look two cells ahead, assuming that there are no obstacles between the robot and that position.
- ***Visibility error***: Due to the risk of the robot colliding with obstacles when moving too close to them, it is necessary to take additional safety measures during path planning. One of the most effective solutions is to apply an erosion process to the map, increasing the size of the obstacles virtually. This creates a safety margin around the obstacles and prevents the robot from planning paths that would bring it too close to them. In this way, the algorithm can generate safer and more reliable trajectories, reducing the possibility of collisions while still allowing the robot to cover as much of the available area as possible.

# 2. MY ALGORITHM

# 3. THE PROCESS

# 4. DIFICULTIES

# 5. VIDEO OF THE ALGORITHM

