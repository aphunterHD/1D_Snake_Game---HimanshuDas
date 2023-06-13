# 1D_Snake_Game---HimanshuDas
In this repository I have implemented 1D snake game using Verilog HDL.
We all know about snake games from our childhood. To re-introduce the game: we start with a snake in a certain space (usually 2-dimensional) with its minimum length. We plant a seed somewhere in the space. The user is then expected to manoeuvre the snake to consume that seed, by doing so the snake grows in its size. Also, if by mistake the snake touches itself during the manoeuvre it returns back to its original minimum length.
In this project I have implemented this game in a one-dimensional space/line. So, user is not expected to do any manoeuvring, an external clock signal does that in the right direction. The user can only decide the seed position. This was done with a thought of implementing the design on FPGA board which consists of 8 LED outputs and 8 DIP switches. The snake can be represented using the LEDs and the DIP switches can be used to feed the location of the seed.
Although the snake can also be caused to move in the opposite direction, but that feature has not yet been implemented.

