# ta2024_SR
The input files of "Terra-Nova, F., Amit, H., 2024. Regionally-triggered geomagnetic reversals. Sci. Rep.,
14, 9639."

For all dynamos simulations E=1E-4, Ra=4E7, Pr=1 and Pm=8. File names are given by the choice of q*,
for example if the file name ends in “q10” then q*=1.0.

Spatial resolution: All models are expanded to maximum spherical harmonic degree and order lmax=170
and the number of radial grid points is Nr=81. The radial description is done by Chebyshev polynomials.

Temportal resolution: courfac=3.0, alffac=1.5, dtmax=1.e-5, alpha=0.6.

For definitions of the spatial and temporal resolution parameters see the Magic documentation: 
https://magic-sph.github.io/inputNamelists/namelists.html
