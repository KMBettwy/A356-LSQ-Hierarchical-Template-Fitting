# A356_Final_Project

Yale's La Silla-QUEST dataset consists of a subset of 25,000 RR Lyrae stars that serve as precise distance indicators and reliable tracers of the galactic halo. These RRL extend to estimated distances of up to 140kpc; however, many of their light curves are sparsely sampled or affected by noise, particularly for the most distant halo stars. To address this, I plan to use Fourier analysis to construct RRab and RRc light-curve templates from a subset of well-sampled stars and apply these templates to the full dataset. I will use a weighted least squares method to compute the Fourier coefficients, with quality cuts that include SNR, minimum observations, and amplitude. Fitting these templates to sparsely sampled light curves in the full LSQ dataset, particularly with estimated distances >100kpc, will enable a more accurate estimation of key parameters such as period, amplitude, and Φ31 values, which in turn leads to more reliable metallicity and distance measurements.

### Table of Contents
1. LSQ dataset (private)
2. Lightcurve Template type ab
3. Lightcurve Template type c
4. Bailey Diagram
