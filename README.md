# Shatter animation by RGB Keyer in a particle system
The Shatter effect works by means of the td_ShatterX.Setting Macro, which contains the td_Centroid.fuse Node. An image is sliced into pieces by means of a mask and breaks apart in a 3D animation. 

### Inputs
- Yellow Input: Visible Image Input
- Green Input: Mask Input; the Mask needs to be created by colored regions separated by increasing red color values (1,2,3,4...Piece Number) for each region. Be careful about compression artefacts or blurring when creating the mask as this will lead to dust like fragmentation.

### Controls
- Output Mode: Choose between 3D or 2D space. 
- Piece Number: Choose the number of regions which are given through the Mask
- Delta: Number of Frames between Finish of Piece Build Up procedure and subsequent Start of Animation (Rest Time)
- Aspect Ratio: Set the Aspect Ratio of the Mask to the Aspect Ratio of the Image
- Random Seed: Changes sequences randomly   
- Speed: Overall speed of expansion and spinning process
- XY-Expansion/Z-Forward/Z-Backward/Spin: Speed of each movement
- Directional Force: Gravitational Forces
- Direction: Direction of Force (-90: downwards, 90: upwards)
- Flicker Intensity: Enables Random Flicker Effect
- Frequency: Speed of Flicker (the smaller the faster the changes)

<img src="https://github.com/Tida-Support/Shatter-animation-by-RGB-Keyer-in-a-particle-system/blob/main/td_ShatterX.png" width="500">

## More Information
https://www.steakunderwater.com/wesuckless/viewtopic.php?p=42724#p42724

## Videos
[![Curved Arrow](https://img.youtube.com/vi/OfnXWhvGQFg/0.jpg)](https://www.youtube.com/watch?v=OfnXWhvGQFg)
[![Curved Arrow](https://img.youtube.com/vi/6INo5jxwMTU/0.jpg)](https://www.youtube.com/watch?v=6INo5jxwMTU)
[![Curved Arrow](https://img.youtube.com/vi/d3qIP1O7GM8/0.jpg)](https://www.youtube.com/watch?v=d3qIP1O7GM8)

## Installation


