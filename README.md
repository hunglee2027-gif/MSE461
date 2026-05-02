# MSE461

# Lab 1 Simulation

This notebook analyzes X-ray reflectivity (XRR) data of a TiN/Al₂O₃ sample and performs thickness estimation and model fitting using the Born approximation.

## Workflow
### First cell
Loads the XRR data (q, R, ΔR) and applies a Fourier transform to estimate the approximate film thickness from the fringe periodicity.

### Section: Fitting
Implements single-layer Born approximation fitting (Air / TiN / Al₂O₃).
This section refines:

film thickness
interface roughness
scale and background

Electron densities are fixed to physically reasonable values.

### Section: Double layer
Implements double-layer Born approximation fitting (Air / Layer 1 / Layer 2 / Al₂O₃).
This model introduces:

a low-density surface layer
a TiN-like main layer

It improves the description of oscillation amplitude but remains limited by the Born approximation.
