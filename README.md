qfdtd
=====

Parallelized FDTD Schrodinger Solver

Pulled from [sourceforge](http://sourceforge.net/projects/quantumfdtd/) originally, heavily modified for my needs. At the moment it's still quite a work in progress.

This code is no longer a general potential solver. Complications that arise from solving the SE in the domain I require has made me break the generality of this code. If you need to solve for degenerate cases of Aluminium Oxide materials; step right up!

Trifid
======

module load blas/1.0.248

module load openmpi-gcc/1.7.0

module load lapack/3.4.2


TODO
====

- [ ] Pull EPS check into parameters so it's not hard coded
