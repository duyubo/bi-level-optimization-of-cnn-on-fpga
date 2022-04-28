# Bi-level Optimization of cnn on fpga
## Overview
*User Input: 
1. Parameter size constraint, e.g. 0.06MB
2. Target device, e.g. xilinx_u200_xdma_201830_2
*Output:
1. The hyperparameter setting for CNN under the parameter size constraint with highest test accuracy
2. The HLS C code (systolic array)
3. Bitstream for xilinx_u200_xdma_201830_2
*Steps:
1. Setup parameter budget
2. Run search algorithm (Evolutinary algorithm or Exhaustive Search) for CNN architectures under the parameter size constraints
3. Get the CNN architecture configuration with the best accuracy and parameter size < parameter budget
4. Set up the configuration of CNN layers and linear layers in C
5. Compile with AutoSA framework which will auatomatically optimize the mapping
6. Build up the bitstream file on FPGA and test 



