Each folder contains the files required to run the simulations in HemeLB, as well as the trajectories file generated from each simulation output.
.xml files contain the simulation parameters
.gmy files are the geometry files in a format suitable for HmeLB
.msh/.vtp files
.vtu files are vtk format file of the geometry

The folders are named as follows : geometry_flowratio_hematocrit. Finally specific cases such as changes in capillary number or geometry asymmetry are also attached at the end of the file name. Abbreviations are as follows :
c = control
lcnr = long compression no recovery
scsr = short compression short recovery
sclr = short compression long recovery

For example, the simulation folder for the control geometry at 10% hematocrit at a 80/20 flow split will be "c_80_20_10pct"

The trajectories file contains the centre of mass of each RBC (in real units) at a given time (in lattice units). Each row is : 
RBC_ID, timestep, x_coordinate, y_coordinate, z_coordinate
