# Rubik's-Cube
A Rubik's Cube Simulator Made Through Unity

I exclusively did this project for people who put their efforts into Rubik's cube solving algorithm to test and debug their code. The simulator provides a platform to directly access the cube's current state over a press of a button. Meanwhile, it can also be used for general purposes, having a good time solving the cube independently.

The simulator is already equipped with a cube solving algorithm, named The Two-Phase Algorithm by [Herbert Kociemba](https://www.speedsolving.com/wiki/index.php/Herbert_Kociemba). It is an external package [Kociemba](https://github.com/Megalomatt/Kociemba).

The Fetch state button is exclusively meant for testing and debugging purposes and is only available for desktop users. The fetch state button saves the cube's current state into a text file named [CurrentState.txt](https://github.com/milind-prajapat/Rubiks-Cube/blob/main/Builds/Windows_x86_x64/Rubiks%20Cube_Data/CurrentState.txt), which is available in the simulator's [data](https://github.com/milind-prajapat/Rubiks-Cube/tree/main/Builds/Windows_x86_x64/Rubiks%20Cube_Data) directory.

## Instructions To Use
One can find the required files to run the simulator in the [Builds](https://github.com/milind-prajapat/Rubiks-Cube/tree/main/Builds) directory of the repository. Android users can use the apk file to install the application, whereas windows users can go with the [Windows_x86_x64](https://github.com/milind-prajapat/Rubiks-Cube/tree/main/Builds/Windows_x86_x64) directory.

You can use the pointing devices as well as the keyboard keys to use the simulator.

## Features
1. Cube automation enables the shuffling of the cube
2. Integration with The Two-Phase Algorithm enables the cube to solve in the lowest number of steps
3. The ability to write the current state of the cube to a text file enables testing and debugging of the Rubik's cube solving algorithm
4. User-friendly and much easy user interface
5. Supports multiple platforms, windows and android both

## Key-Bindings
```
F - Front Face
L - Left Face
B - Back Face
R - Right Face
U - Up Face
D - Down Face

M - Centre-Right Vertical
S - Centre-Left Vertical
E - Centre Horizontal

X - Rotates Cube on R
Y - Rotates Cube on U
Z - Rotates Cube on F

P - Shuffle
Q - Solve
C - Get Current State

Uppercase turns 90° clockwise, and Lowercase turns 90° counter-clockwise
```

## References
1. [Windows Build](https://drive.google.com/file/d/1yPU8f04ILZ6PNuArOsjJkt3EMk4QQR_F/view?usp=sharing)
2. [Android Application](https://drive.google.com/file/d/1ExQ5nqQ2iixKeT88FqmeG6X6uyF3YHdG/view?usp=sharing)
