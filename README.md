October 14, 2019
Author: Sean McGovern

This is the Adaptive Mesh Refinement portion of the Coupled Parallel Pressure Level Set application. 

It is based on dealii (dealii.org) and therefore requires a working installation of the dealii library (version 8.5 or later) to run. 

This code is set up to run with in parallel with MPI and PETSc.

The purpose of this development code is to document progress towards a fully
functional dynamic local adaptive feature of the CPPLS basin simulator.

All files were authored by Sean McGovern and are placed under the MIT license, with the exception of CPPLS_AMR/source/level_set_solver.h which was authored by Manuel Quezada de Luna and adapted for this project.
