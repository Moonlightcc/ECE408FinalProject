## Forward Convolutional Layer With Cuda

#### Introduction

Final project for the Fall 2021 ECE408 Applied Parallel Programming @ UIUC.

This project implements and optimizes the forward-pass of a convolutional layer using CUDA.

#### Optimizations Implemented

- Tiled shared memory convolution
- Weight matrix (kernel values) in constant memory
- Tuning with restrict and loop unrolling
- Using Streams to overlap computation with data transfer
