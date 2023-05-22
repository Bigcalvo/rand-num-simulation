# Simulation and Generating Random Numbers
The generation of random numbers is foundational to the field of simulation. These generators power the simulation itself, and without good generators that closely mimic the underlying probability distribution, your simulation won't be useful. This project focused on this idea of sussing out "good" generators, specifically looking at Uniform (0,1) generation. "Goodness" was determined by the results of a Chi-Squared Goodness-of-Fit test, the Runs Test, and the Serial Correlation test. Generators examined include the Desert Island, Tausworthe, RANDU, Mersenne-Twister and Wichmann-Hill.

The R markdown file includes code alongside insights, can can be run. 
