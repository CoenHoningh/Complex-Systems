# The inleveren directory contains all final code/data used for the project with documentation, the notebooks in the root directory are unused and unmaintained and left for archiving purposes.

This project contains five ipython notebook files simulating the Gray-Scott reaction diffusion model. Each file contains the code to run the simulation.

Contributors:
-------------
- Coen Honingh (10988459)
- Tristen Assenmacher (12168599)
- Toby van Gastelen (11260572)
- Lennart Mettrop (10432973)



Requirements:
-------------
To run the code, the following python packages must be installed:
- numpy
- scipy
- matplotlib
- seaborn
- numba
- tqdm
- sklearn
- iPython



File descriptions:
------------------

Gray_scott_vis.ipynb:
This file plots visualisation of the results from the simulation for different parameter values. A trajectories where the syste goes from stable dots to chaotics dots is visualised as well as a transition from stable dots to worm patterns. Also the initial conditions are plotted.


Gifjes.ipynb:
This file contains the code used for making the animations of the two trajectories.


Full_fisher_matrix.ipynb:
This file contains the code to calculate the fisher information matrix. Also plots are made to show how the fisher information changes over the two trajectories.


Bulk_runs_entropy.ipynb:
This file contains the code to plot the phase plots for the Shannon Entropy as well as the plots themselves. This file also contains plots of the Shannon Entropy and Fisher Information over the two transitions.


Distribution_animation.ipynb:
This file contains the code for the animation of the distributions of pattern sizes over the two trajectories.
