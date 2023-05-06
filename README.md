# LaminarLabeling
LaminarLabeling takes Blackrock .ns6 files and identifies cortical boundaries.
For a detailed description of the methodology please see our manuscript's pre-print:
> A ubiquitous spectrolaminar motif of local field potential power across the primate cortex
>
> Diego Mendoza-Halliday, Alex J. Major, Noah Lee, Maxwell Lichtenfeld, Brock Carlson, Blake Mitchell, Patrick D. Meng, Yihan (Sophy) Xiong, Jacob A. Westerberg, Alexander Maier, Robert Desimone, Earl K. Miller, André M. Bastos
> bioRxiv 2022.09.30.510398; doi: https://doi.org/10.1101/2022.09.30.510398
> This article is a preprint and has not been certified by peer review

## Example data
This repository takes an .ns6 file recorded from 32 channel Plexon V-Probes acutely penetrated into Macaque V1. Example data is freely availabley upon request: brock.m.carlson@vanderbilt.edu.

## Instructions
run LaminarLabeling in MATLAB
Figures generated show multi-unit-activity, local-field-potentials, current-source-density, and power-spectral-density measures across laminar depth to evoked visual potentials (flashes)
Estimated depth measures are based on the gamma-beta cross in mean power-spectral-density, as discussed in the manuscript.
