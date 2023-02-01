# plumed_input_supercooled_water
Input related to supercooled water simulations in Journal of Chemical Physics 158, 014502 (2023).

The simulation is umbrella sampling using the S component of path collective variables based on the PIV metric.

The pdb files are necessary, together with plumed.dat, to run the simulation, 
since they contain the two reference structures used to define the collective variables.

The simulation is very slow (about 9 ns/day on 40 cores) due to the high cost of the path-PIV variable.

Tested on gromacs 2021.4 with plumed-2.7.4
