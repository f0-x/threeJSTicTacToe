# A Simple Tic Tac Toe Board Game Build using Three JS (React Three) 🎨
![alt text](https://github.com/f0-x/threeJSTicTacToe/blob/master/gif_preview.gif "Local Preview")

## Main Packages Used
* Three JS via React Three Fiber Renderer esp. build for React Applications. 
* Drei : Basically a set of helper functions to consume Three JS functionalities in React App
* Postprocessing: A Wrapper component to wrap our React Three app for Three JS visual effects
* Framer Motion (3d): A Library of sick 2D/3D animations used for Board Events
* Immer: Used to handle immutable board states across the games.
* Vite with Vitest: Modern buld tool and an awesome testing framework which is BLAZINGLY fast 🔥
* Leva: A GUI toolbox that allows us to customize our React Three elements easily.

## Why are there 4 cells in each Tic-Tac-Toe plane view ?
Regular Tic Tac Toe exists in Two-dimensional view which is represented by a 3x3 plane. To increase the dimension to 3D we want a cube that is 4x4x4. The reason each side has a length of 4 in 3D is that if we kept it at length 3, the first player will always win if they go in the middle. So to remove this unfairness of logic while implementing a 3D view for a Tic-Tac-Toe board game, I have added an extra cell for each plane. 