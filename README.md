# StableDepth

## Defining a New Approach to Stable Video
1. Text2Image generation
1. Export a high resolution monocular depth map from the image
1. Import the depth map and the image to a lightweight 3d rendering engine such as three.js
1. Using the depth map, create a simple mesh and apple the image as a texture
1. Move the camera position in the way desired - can be automated
1. From camera motion, export new depth map information and image textured mesh information
1. Using these newly created frames, apply a control net to a batch process using the new depth frames and reference images or possible as Image2Image