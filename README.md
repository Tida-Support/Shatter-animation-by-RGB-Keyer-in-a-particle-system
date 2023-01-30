# Shatter animation by RGB Keyer in a particle system
The Shatter effect works by means of the td_ShatterX.Setting Macro, which contains the td_Centroid.fuse Node. An image is sliced into pieces by means of a mask and can break apart in a 3D animation. 

### Inputs
- Yellow Input: Visible Image Input
- Green Input: Mask Input; the Mask needs to be created with colored regions separated by increasing red color values (1,2,3,4...Piece Number) for each region.

### Controls
- Output Mode: Choose between 3D or 2D space. 
- Piece Number: Choose the number of regions which are given through the Mask
- Delta: Number of Frames between Finish of Piece Build Up procedure and subsewuent Start of Animation (Rest Time)
- Aspect Ratio: Set the Aspect Ratio of the Mask to the Aspect Ratio of the Image
- Random Seed: Changes sequences randomly   
- Speed: Overall speed of expansion and spining process
- XY-Expansion/Z-Forward/Z-Backward/Spin: Speed of each movement
- Directional Force: Gravitational Forces
- Direction: Direction of Force (-90: downwards, 90: upwards)
- Flicker Intensity: Enables Random Flicker Effect
- Frequency: Speed of Flicker (the smaller the faster the changes)

## Videos
## Installation
