# DARK MATTER IN DISEQUILIBRIUM: THE LOCAL VELOCITY DISTRIBUTION FROM SDSS-GAIA
## Work published as [arXiv:1807.02519](https://arxiv.org/abs/1807.02519), by Lina Necib, Mariangela Lisanti, and Vasily Belokurov

For any questions, please email lnecib at caltech dot edu. 

### Abstract:

We use the distribution of accreted stars in SDSS-Gaia DR2 to demonstrate that the local dark matter halo may not be in equilibrium and that a non-trivial fraction is in substructure. Using a mixture likelihood analysis, we separate the contributions of an old, isotropic stellar halo and a younger anisotropic population. The latter dominates and is uniform within Galactocentric radii of 7.5–10 kpc and abs(z) > 2.5 kpc. It can be explained as the tidal debris of a disrupted massive satellite on a highly radial orbit, and is consistent with mounting evidence from recent studies. Simulations that track the tidal debris from such mergers find that the dark matter traces the kinematics of its stellar counterpart. If so, our results indicate that the majority of the local dark matter that is sourced by luminous satellites is in kinematic substructure referred to as debris flow. These results challenge the Standard Halo Model, which is highly discrepant with the distribution recovered from the stellar data, and have important ramifications for the interpretation of direct detection experiments.

### Datasets:

These files are the most up-to-date source for the velocity distribution. We recommend using them over the analysis from [arXiv:1708.03635]. Note that we use V,pec = (U, V, W ) = (8.50,13.38, 6.49) km/s (Coskunoglu, B., Ak, S., Bilir, S., et al. 2011, MNRAS, 412, 1237) and the local circular velocity v = 235 km/s. For the Galctocentric velocities, please use the best fit functions in the paper.

We provide the following functions:
* f(v) total: this is the velocity distribution in heliocentric frame that sums both the substructure and halo components with their relative contributions, normalized to 1.
* f(v) substructure: this is the substructure component's velocity distribution in heliocentric frame, normalized to 1.
* f(v) halo: this is the halo component's velocity distribution in heliocentric frame, normalized to 1.
* f(v) SHM: this is the standard halo model's velocity distribution in heliocentric frame, normalized to 1.
* g(vmin): The integral of f(v)/v in the heliocentric frame of the total distribution.

#### Note:
(September 26, 2018) An change to the relative contributions of the substructure and the virialized component has been updated in the f(v) total. In upcoming work (Necib, Lisanti, Garrisson-Kimmel et al. 2018) we will show how to obtain the contribution of mergers relative to the virialized component. This will include an error band. The result is as follows:

$$ f(v) = $$








# Empirical Velocity Distribution of Dark Matter
## Work published as [arXiv:1708.03635](https://arxiv.org/abs/1708.03635), by Jonah-Herzog-Arbeitman, Mariangela Lisanti, and Lina Necib

### Abstract:
The local velocity distribution of dark matter plays an integral role in interpreting the results from direct detection experiments. We previously showed that metal-poor halo stars serve as excellent tracers of the virialized dark matter velocity distribution using a high-resolution hydrodynamic simulation of a Milky Way--like halo. In this paper, we take advantage of the first \textit{Gaia} data release, coupled with spectroscopic measurements from the RAdial Velocity Experiment (RAVE), to study the kinematics of stars belonging to the metal-poor halo within an average distance of ∼5 kpc of the Sun. We study stars with iron abundances \[Fe/H\] <−1.5 and −1.8 that are located more than 1.5 kpc from the Galactic plane. Using a Gaussian mixture model analysis, we identify the stars that belong to the halo population, as well as some kinematic outliers. We find that both metallicity samples have similar velocity distributions for the halo component, within uncertainties. Assuming that the stellar halo velocities adequately trace the virialized dark matter, we study the implications for direct detection experiments. The Standard Halo Model, which is typically assumed for dark matter, is discrepant with the empirical distribution by ∼6σ and predicts fewer high-speed particles. As a result, the Standard Halo Model overpredicts the nuclear scattering rate for dark matter masses below ∼10 GeV. The kinematic outliers that we identify may potentially be correlated with dark matter substructure, though further study is needed to establish this correspondence. 


### Datasets:

We find two velocity distributions of these metal poor stars, one for each of the \[Fe/H\] cuts. The files are in this repository and can be obtained by forking/downloading this repository.

heliocentric_velocity_feH15.txt : Analysis with [Fe/H]<-1.5

heliocentric_velocity_feH18.txt : Analysis with [Fe/H]<-1.8
