## MRI_FISTA - A collection of FISTAs for MRI

 - Matthew Muckley - Matthew.Muckley@nyumc.org

------------------------------------------------------------------------------
INFO:
------------------------------------------------------------------------------
A library for accelerated FISTA algorithms tailored for MRI.

The library includes:

 - BARISTA: B1-Based, Adaptive Restart, Iterative Soft-Thresholding
   Algorithm, a fast algorithm tailored for SENSE MRI
 - OM-BARISTA: BARISTA with optimized momentum augmentation

------------------------------------------------------------------------------
REQUIREMENTS:
------------------------------------------------------------------------------

 - Requires installation of the Michigan Image Reconstruction Toolbox (MIRT)
   available at https://web.eecs.umich.edu/~fessler/code/
 - MATLAB 2011 or higher

------------------------------------------------------------------------------
RUN:
------------------------------------------------------------------------------

 - see ir_barista_example.m or ir_barista_test2.m for test examples

------------------------------------------------------------------------------
SUPPORTING MATERIAL:
------------------------------------------------------------------------------

 - see "Fast parallel MR image reconstruction..." by Muckley et al. for 
   BARISTA
 - see "Momentum optimization for iterative shrinkage..." by Muckley et al.
   for OM-BARISTA
