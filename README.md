## MOCASSIN-3.0
[![Build Status](https://travis-ci.org/equib/MOCASSIN-3.0.svg?branch=master)](https://travis-ci.org/equib/MOCASSIN-3.0)
[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/equib/mocassin-3.0)
[![GitHub license](https://img.shields.io/aur/license/yaourt.svg)](https://github.com/mocassin/MOCASSIN-3.0/blob/master/LICENSE)

**MOnte CArlo SimulationS of Ionized Nebulae**, Version 3.0

*3D Monte Carlo X-Ray Enabled Photoionization and Dust Radiative Transfer Code*

Copyright (C) 2007 Barbara Ercolano 

### Installation

How to compile:

    make mocassin
    make mocassinWarm
    make mocassinOutput
    make mocassinPlot

What typical packages required to compile mocassin on linux:

    gcc openmpi

or

    intel/mpi

How to clean:

    make clean
     
How to run:

    mpirun -np N ./mocassin

where N is number of processors for parallel computing.

How to run mpirun on a supercomputer:

In the [batches folder](https://github.com/equib/mocassin-models/tree/master/batches) of [mocassin-models](https://github.com/equib/mocassin-models), there are running batch examples for different job scheduling systems. 

To submit a batch file on the Portable Batch System (*PBS*):

     qsub mocassin_run.job

To submit a batch file on the Sun Grid Engine (*SGE*):

     qsub mocassin_run.job

To submit a batch file on the Simple Linux Utility for Resource Management (*SLURM*): 

     sbatch mocassin_run.sh

### References

* Ercolano, B., Young, P. R., Drake, J. J., & Raymond, J. C, "X-Ray Enabled MOCASSIN: A Three-dimensional Code for Photoionized Media", [ApJS, 175, 534-542, 2008](http://adsabs.harvard.edu/abs/2008ApJS..175..534E)

* Ercolano, B., Drake, J. J., Raymond, J. C., & Clarke, C. C., "X-Ray-Irradiated Protoplanetary Disk Atmospheres. I. Predicted Emission-Line Spectrum and Photoevaporation", [ApJ, 688, 398-407, 2008](http://adsabs.harvard.edu/abs/2008ApJ...688..398E)

* Ercolano, B., Clarke, C. J., & Drake, J. J., "X-Ray Irradiated Protoplanetary Disk Atmospheres. II. Predictions from Models in Hydrostatic Equilibrium", [ApJ, 699, 1639, 2009](http://adsabs.harvard.edu/abs/2009ApJ...699.1639E)

