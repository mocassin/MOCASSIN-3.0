## MOCASSIN-3.0
[![Build Status](https://travis-ci.org/equib/MOCASSIN-3.0.svg?branch=master)](https://travis-ci.org/equib/MOCASSIN-3.0)
[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/equib/mocassin-3.0)

**MOnte CArlo SimulationS of Ionized Nebulae**, Version 3.0

Copyright (C) 2007 Barbara Ercolano 

### Installation

How to compile:

    make mocassin
    make mocassinWarm
    make mocassinOutput
    make mocassinPlot

How to clean:

    make  clean
     
How to run:

    mpirun -np N ./mocassin

where N is number of processors for parallel computing.

### References

* Ercolano, B., Clarke, C. J., & Drake, J. J., [ApJ, 699, 1639, 2009](http://adsabs.harvard.edu/abs/2009ApJ...699.1639E)

* Ercolano, B., Drake, J. J., Raymond, J. C., & Clarke, C. C., [ApJ, 688, 398-407, 2008](http://adsabs.harvard.edu/abs/2008ApJ...688..398E)
