# MRI_FISTA - A collection of FISTAs for MRI reconstruction

A library for accelerated fast iterative soft thresholding (FISTA) algorithms tailored for MRI reconstruction.

The repository includes:

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

### References

 - MJ Muckley, DC Noll, JA Fessler. [Fast Parallel MR Image Reconstruction via B1-Based, Adaptive Restart, Iterative Soft Thresholding Algorithms (BARISTA))](http://doi.org/10.1109/TMI.2014.2363034). *IEEE Transactions on Medical Imaging*, 34(2):578–588, 2015.
 - MJ Muckley, Douglas C. Noll, and Jeffrey A. Fessler. [Momentum optimization for iterative shrinkage algorithms in parallel MRI with sparsity-promoting regularization](https://web.eecs.umich.edu/~fessler/papers/lists/files/abs/15/muckley-15-mof.pdf). In *ISMRM*, page 4400, 2014.
