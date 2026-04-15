The name of the code is 'lmgs', an abbreviation of 'Langmuir Methods for Gas Storage'.

The code 'lmgs' calculates the gas storage capacities of a solid material, by means of the Langmuir method or model.

The code calculates the volumetric and gravimetric capacities. It calculates the total and usable capacities.

The present version calculates the storage capacities of any gas inside a solid material.

It uses the Langmuir fractional coverage equation [1-3]

The code 'lmgs' is written in fortran and only for Unix/Linux environments.

It has been compiled and tested on different hosts based on Unix/Linux

The source files and some examples of input and output files are in the branches of this project.

To compile the code: 
a) tar zxvf lmgs-source.tar.gz 
The source files are in the directory lmgs/source
b) cd lmgs/source
c) Enter 'make' or 'make -s'

The file lmgs-alf.tar.gz contains some examples of input and output files, applied to ALF, an Al-based MOF.
To get those files, enter 'tar zxvf lmgs-alf.tar.gz'. The files are in the directory lmgs/alf

Bibliography:

[1] T. L. Hill, Statistical Mechanics: Principles and Selected Applications, McGraw–Hill, New York, 1956.

[2] M. S. Suzuki, Langmuir adsorption: application of grand canonical ensemble, Tech. rep., Department
of Physics, SUNY at Binghamton, Accessed April 9, 2026 (2023).

[3] Cersonsky Lab, Application of independent subsystems: the Langmuir isotherm. advanced thermodynamics for 
chemical engineers, lecture notes, https://cersonsky-lab.github.io/cbe710-notes/lecture_files/Lecture7.html, 
Accessed April 9, 2026 (2023).
