# A356_Final_Project

Yale's La Silla-QUEST dataset consists of a subset of 25,000 RR Lyrae stars that serve as precise distance indicators and reliable tracers of the galactic halo. These RRL extend to estimated distances of up to 140kpc; however, many of their light curves are sparsely sampled or affected by noise, particularly for the most distant halo stars. As RR Lyrae stars have characteristic, periodic lightcurves, fitting the sparsely sampled lightcurves using a predetermined template library that accurately spans the range of RRab shapes will enable a more precise estimation of key parameters such as period, amplitude, and Φ31 values, which in turn leads to more reliable metallicity and distance measurements. In this project I use agglomerative hierarchical clustering to construct RRab light-curve templates from a subset of well-sampled stars and applied these templates to sparsely sampled stars within the dataset. I also explore using a convolutional autoencoder in order to create a fully continuous template library to be applied to the RRL dataset. 

### Table of Contents
1. LSQ dataset samples ('template' stars and sparsely fit stars)
2. 22 smoothed and clustered RR Lyrae lightcurve templates trained on a high quality subset of LSQ stars
3. Jupyter notebook detailing methods, steps and analysis

### Relevant Papers
1. Sesar, Branimir, et al. “Light Curve Templates and Galactic Distribution of RR Lyrae Stars from Sloan Digital Sky Survey Stripe 82.” The Astrophysical Journal, vol. 708, 2010, pp. 717–741.
2. Kovács, G., and G. Kupi. “Computation of the Fourier Parameters of RR Lyrae Stars by Template Fitting.” Astronomy & Astrophysics, vol. 462, no. 3, 2007, pp. 1007–1016.
3. Gavrilchenko, Tatyana, et al. “A Mid-Infrared Study of RR Lyrae Stars with the Wide-field Infrared Survey Explorer All-Sky Data Release.” Monthly Notices of the Royal Astronomical Society, vol. 441, no. 1, 2014, pp. 715–725.
4. Zinn, R., et al. “La Silla Quest RR Lyrae Star Survey: Region I.” The Astrophysical Journal, vol. 781, no. 1, 2014, p. 22.
