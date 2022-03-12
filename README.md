# RLD
Code to calculate root-mean-squared lattice distortion (RLD).  
The RLD code generates `all8NearestNeighbours.txt` file which will contain all the `first nearest neighbors` of every atom.

## Steps
1. Install [pymatgen](https://pymatgen.org) and [vasputil](https://github.com/jabl/vasputil)
2. Get the relaxed CONTCAR file from the VASP run.
3. Copy the `get_8NearestNeighbours.sh` file to the directory.
4. Get the relaxed lattice parameter from the earlier CONTCAR file.
5. Execute the program as `./get_8NearestNeighbours.sh <lattice parameter from bulk relaxation>`
6. The results will be shown on the terminal screen.
