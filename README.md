# Condensate_analyses
These MATLAB codes are used in the paper of Shu et al. "Mesoscale molecular assembly is favored by the active, crowded cytoplasm".

There are three folders here. First is the "Particle_tracking_vs_Intensity" folder, which analyzes the experimental data. Microscope images and time course movies of droplets are first processed through FIJI plugin 'Trackmate', which generates '.csv' files indicating spots properties using particle detection function and '.xlm' files indicating particle tracking trajectories. The codes then use these '.csv' and '.xlm' files as inputs and analyze droplets properties including the mean pixel intensity, total droplet intensity, number of droplets etc, as well as droplets trajectories properties including diffusivity, angle correlation function and normalized velocity autocorrelation functions. Details of how to run functions can also be found in the word documents located in the folder: "Program running instructions.docx".

The second is "Java_MD_simulations" folder, which includes molecular dynamics simulation program using Java8 "Java_MD_simulation_program.jar" and subsequent analyses using Jupyter notebook "Subsequent_analyses_after_simulation.ipynb". There is also an example parameter text file "simulation_input_parameter_file", which can be used for running MD simulations by execute "java -jar -Xmx8G Java_MD_simulation_program.jar simulation_input_parameter_file" in the terminal.

The third is "HOOMD_blue_MD_simulations" folder, which includes moleculuar dynamics simulation program using HOOMD-blue "" and subsequent analyses using Jupyter notebook "Subsequent_analyses.ipynb".
