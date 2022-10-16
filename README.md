# test
## Introduction
Recursive median filter Verilog build library. It includes two window sizes of 3×3 and 5×5. The hardware platform used in this project is Xilinx ynq UltraScale+ xczu9eg-ffvb1156-2-e.
## Modules
* `top.v` -- 3×3 window top module.
* `select5_3.v` -- 3x3 window pre-processing module. Exclude the maximum and minimum values in the last 2 columns of the current window (window center data does not participate in pre-processing).