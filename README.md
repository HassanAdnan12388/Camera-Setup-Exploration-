# Camera-Setup-Exploration-
Camera Setup Exploration and 3D Projection Analysis using a LEGO image

# Overview
This project explores the impact of various camera parameters (extrinsic and intrinsic) on the projection of a 3D model (a LEGO figure) onto a 2D image plane. By manipulating focal length, camera position, and rotation, we investigate how these factors influence the perceived size, depth, and perspective of the object in the resulting image.


# Part 1: Exploring the Impact of Focal Length 
Objective: Investigate how varying focal length (400mm, 800mm, 1600mm) affects the projection of the 3D model while keeping the camera position fixed.

**Implementation:**
- Create projection matrices for each focal length.
- Project 3D points onto the 2D plane.
- Visualize the 2D projections using visualize_points().
- Analyze the changes in field of view, scale, and perceived depth with increasing focal length.
- Graphs: The graphs will demonstrate a clear decrease in the size of the projected figure as the focal length increases. This visually confirms the concept of "zooming in" with longer focal lengths.


# Part 2: Exploring the Effect of Camera Position 
**Objective**: Examine how changing camera position (center, right, up) affects the projection while maintaining a constant focal length (1200mm).

**Implementation** :
- Create projection matrices for each camera position.
- Project 3D points and visualize the 2D projections.
- Analyze the changes in perspective and orientation of the 3D model as the camera position shifts.
- Graphs: The graphs will show how the figure appears to "move" relative to the image frame as the camera position changes. For example, shifting the camera to the right will cause the figure to appear to move to the left in the projection.



# Part 3: Telephoto Effect vs. Camera Position 
**Objective**: Compare the effects of different combinations of focal length and camera distance on the projection.

# Close-up: 600mm focal length, z = -500 units.
# Telephoto: 1800mm focal length, z = -5000 units.
# Medium: 1200mm focal length, z = -1000 units.

**Matching Perspective with Different Focal Lengths**

# Objective: Determine the necessary camera translation to achieve the same projection with a reduced focal length (500mm) as with an initial setup of 5000mm focal length and a distant camera position.
**Implementation:**
- Calculate the required camera translation.
- Create projection matrices for both setups.
- Project 3D points and visualize the 2D projections to verify the match.
- Analyze the relationship between focal length and camera distance to maintain a consistent projection.

# Part 4: Exploring the Impact of Camera Rotation (10 Marks)
**Objective**: Investigate how camera rotation around the Y-axis (0°, 30°, 60°, 90°) affects the projection while keeping focal length and distance constant.


