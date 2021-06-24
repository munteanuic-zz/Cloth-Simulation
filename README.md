# Cloth Simulation

## Authors
Ioana Munteanu & Sid Lin

## Demo
[Click here!](https://www.youtube.com/watch?v=6N6bRzey-rI)

## Installation
1. Download [Processing](https://processing.org/download/).
2. Clone the repository.
3. Open it in Processing and press 'Run'.

## Description
 - The 3D cloth simulation was designed by drawing multiple independent ropes which all hang and swing freely and bind to each other using some horizontal ropes.
 - The cloth is able to naturally fall on a red sphere which can be controlled by the user. 
 - The cloth is designed to have a natural look by its real-time velocity, design (green and blue triangles), and by the forces that act on it, such as air resistance or drag force. 
 - The user can move and drag the image by using the mouse.
 - FPS is tracked using the processing console output.
 
## User interaction
 - Scroll wheel: move in/out
 - Mouse drag: rotate/pan camera
 - WASD: move ball

## Programming language
- Processing 

## Difficulties
- Implementing the drag force was particularly difficult because of the tuning of the parameters. This issue was solved by creating only one constant that was the product of all constants involved.
- Adding a texture to the Cloth while keeping its velocity as natural as possible. A png file was slowing down the simulation, so the cloth was styled using some colored triangles.
- Getting the simulation to work with large n (number of springs) values was difficult, due to hardware limitations. Spring counts larger than 25 or 30 would cause extremely slow ball and cloth movement.


