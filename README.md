# PSDE Algorithm Documentation

## Introduction

The PSDE algorithm is a powerful optimization technique designed for single objective constrained numerical optimization test functions. This repository contains the core PSDE implementation along with instructions on how to use it effectively.

## Test Function Replacement

- **CEC20 Test Function**: Place the `cec20_func.cpp` and `input_data` folders in the same directory as the algorithm. Set this folder as the current path.
- **CEC22 Test Function**: Replace `cec20_func.cpp` and `input_data` with `cec22_func.cpp` and `input_data` from the CEC22 test function. Modify the `opt` array in `Introd_Par` as indicated in the code comments.

## Running PSDE

To execute PSDE, follow these steps:

1. Run `main_loop.m` for numerical optimization.
2. Set the problem dimensions in `main_loop.m` to `n=10` or `n=20`, as required.
3. The final result statistics will be displayed in the Matlab command window and saved in the `result_` folder.
