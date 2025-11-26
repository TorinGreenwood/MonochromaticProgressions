Companion code for the paper, "Exploring antisymmetry while minimizing monochromatic arithmetic progressions" by Torin Greenwood and Ashley Skalsky.

## Contents:

* MonochromaticOptimizationCode is Python code including:
  * Optimization methods that compute locally optimal colorings of the k-star, rectangle, and circle across varying regimes
  * Plotting code to display each type of coloring
  * Code to draw the weighted BCG diagram for a coloring
  * Sample simulations for the circle and rectangle
 
* AreaPolynomialCode is SageMath code including:
  * Code to convert a coloring into a weighted area polynomial, representing the weighted area of monochromatic regions from a BCG diagram
  * A runthrough of this code on the conjectured optimal coloring
  * Note: this code is in SageMath to enable the use of symbolic variables in polynomials

* kStarAdjacentRegimeSimulations is Python code including:
  * Code to compute and plot locally optimum colorings of the k-star
  * Several simulations for the k-star under the adjacent regime with variations in arm length and number of arms
  * Code to generate equivalent colorings respective of red/blue and pink/purple swaps
  * Code to calculate the relative difference between given colorings
  * Bin categorzations for all local optima in each simulation

* kStarAllRegimeSimulations is Python code including:
  * Code to compute and plot locally optimum colorings of the k-star
  * Several simulations for the k-star under the all regime with variations in arm length and number of arms
  * Code to generate equivalent colorings respective of red/blue and pink/purple swaps
  * Code to calculate the relative difference between given colorings
  * Bin categorzations for all local optima in each simulation
