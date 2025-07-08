# Brain_3D_simulation
The code used for multi-scale human brain modeling is all encapsulated in a Singularity image. myjob.pb is a script for distributing computing tasks across nodes.
To submit the task, please run the command "qsub myjob.pbs" on the terminal of the computer cluster with multiple nodes.
The "data" folder contains the three-dimensional ultrasound simulation data of the human brain that we have calculated. The data format is vtu. It can be opened using the open-source visualization software Paraview.
