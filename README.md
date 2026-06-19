# Reshape-Matrix
Grid data interpolation: bi-linear, bi-square, and bi-cubic. 

*Chebyshev or Fourier filtering is not included.*

Introduced as a lightweight, local $O(1)$ framework to implement custom filtering, from simple linear-cubic/square difference thresholds to more complex boundary-clamping constraints. 

Can be handy for numerical methods, high-performance computing (HPC) simulations, and custom graphics shading, where global splines fail due to excessive space information or matrix rank deficiency.
