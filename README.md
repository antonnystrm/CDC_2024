# CDC_2024
This Repository contains Matlab code for reproducing figures and numerical results in the associated article INSERT ARTICLE HERE


# MotivatingExample2.m
This script runs a single system identification experiment on data generated from a known nominal model and random input and measurement noise. The resulting nyquist plot of the identified system is plotted and uncertainty regions displayed.

# realize_kappa.m
This script runs on the same premise as the previous with the same nominal model and system identification experiments being performed. 1000 identifications are performed on the same system using different random input and measurement noise and the chordal distance between the identified system and the nominal model are computed for every freqency on a grid over each realization. These are then plotted in a 3d plot and as a heatmap. Furthermore the peak chordal distance and the frequency at which this is achieved are computed for each realization and plotted in separate histograms to provide an indication of how a distribution of those quantities might look like for certain cases.

# Fkw.m
This script provides a numerical example of the main result of the associated paper for a Gaussian distribution with the entire complex plane as its support set and plots the resulting CDF of the chordal distance.
