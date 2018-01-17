# MRI_FISTA - A collection of FISTAs for MRI

 - Matthew Muckley - Matthew.Muckley@nyumc.org

## Info

A library for accelerated FISTA algorithms tailored for MRI.

The library includes:

 - BARISTA: B1-Based, Adaptive Restart, Iterative Soft-Thresholding
   Algorithm, a fast algorithm tailored for SENSE MRI
 - OM-BARISTA: BARISTA with optimized momentum augmentation

An older version of these scripts is included in the [MIRT](https://web.eecs.umich.edu/~fessler/code/)

### Requirements

 - Requires installation of the [Michigan Image Reconstruction Toolbox (MIRT)](https://web.eecs.umich.edu/~fessler/code/)
 - MATLAB 2011 or higher

### Test Examples

 - see matlab/ir_barista_example.m or matlab/ir_barista_test2.m for test 
   examples

### Supporting Material

BARISTA
 - see [BARISTA](http://doi.org/10.1109/TMI.2014.2363034) by Muckley et al.
 - see "Momentum optimization for iterative shrinkage..." by Muckley et al.
