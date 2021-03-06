## Simulated Light Curves
The subdirectory ```simulatedLightcurves``` contains the simulated light curves and 
supplementary table. 

* [Simulated light curves] The file ```simulated_lightcurves.tgz``` contains 100,000 simulated light curves, generated following the procedure of our paper. Each light curve is stored in one file with three columns: MJD, *I* magnitude and uncertainty. The file name is based on the original OGLE variable ID from which it is generated (also listed in the next item).  
* [Mira variables] The file ```supp_table.dat``` is the table summarizing the relevant properties of OGLE LMC Miras from [Soszynski et al. (2009)](http://adsabs.harvard.edu/abs/2009AcA....59..239S) that were used to simulate the light curves: OGLE ID, main period and mean *I* & *V* magnitudes. It includes some extrapolated values of *V* for objects with missing data (suitably identified with a "*"). This table can be used to compare true versus derived periods and to generate Period-Luminosity relations.

